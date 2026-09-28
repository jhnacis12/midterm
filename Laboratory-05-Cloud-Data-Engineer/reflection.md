# Reflection

## 1. Why is object storage suitable for storing millions of images?

Object storage is suitable because it is designed to store large amounts of unstructured data such as images, videos, and documents. Files are stored as objects inside buckets, making the data easier to organize and manage.

## 2. What is the advantage of MinIO compared to cloud providers like AWS S3?

MinIO provides S3-compatible object storage that can be deployed and managed by the organization itself. It can be useful when an organization wants more control over where its data is stored and how the storage system is managed.

## 3. What challenges did you encounter during deployment?

One challenge I encountered was getting the MinIO Docker image to download correctly in the KillerCoda environment. I also had to make sure the Docker command was entered correctly because incorrect formatting caused Docker errors.

## 4. How would you secure MinIO in a production environment?

I would use strong administrator credentials, protect the MinIO server from unauthorized access, use secure connections such as HTTPS, and regularly manage users and permissions. I would also make backups of important data.

## 5. What did you learn about object storage?

I learned that object storage is different from block and file storage. It is especially useful for large amounts of unstructured data such as images. I also learned how Docker can be used to deploy an object storage service such as MinIO.
