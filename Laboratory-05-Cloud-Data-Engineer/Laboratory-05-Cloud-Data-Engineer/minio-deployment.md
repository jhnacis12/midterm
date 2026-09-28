# MinIO Deployment

## Deployment Command

The MinIO server was deployed using Docker with the following command:

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
minio/minio server /data --console-address ":9001"
```

## Web Console Port

The MinIO Web Console was accessed using port **9001**.

## Bucket Name

The storage bucket created for the client was:

`client-photos`

## Environment Variables

The `-e` flags define environment variables for the MinIO container.

* `MINIO_ROOT_USER=cloudadmin` sets the administrator username.
* `MINIO_ROOT_PASSWORD=CloudNova2026!` sets the administrator password.

These credentials are used to log in to the MinIO Web Console.
