# Cloud Storage Types Research

| Storage Type   | Description                                                            | Primary Use Case                                                                  | Cloud Provider Example |
| -------------- | ---------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ---------------------- |
| Block Storage  | Stores data in fixed-size blocks that can be accessed individually.    | Virtual machines, databases, and applications that need high-performance storage. | AWS EBS                |
| File Storage   | Stores data as files organized in folders and directories.             | Shared files and applications that need a common file system.                     | AWS EFS                |
| Object Storage | Stores data as objects together with metadata and a unique identifier. | Large amounts of unstructured data such as images, videos, and backups.           | AWS S3                 |

### Why Object Storage?

Object Storage is the best choice for the client's user-uploaded images because it is designed to store large amounts of unstructured data. It can also scale to handle millions of images while allowing applications to access the stored objects when needed.
