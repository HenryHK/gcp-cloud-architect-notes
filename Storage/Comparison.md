# Comparison storage options

## Tech details

| Comparison/Options | Cloud Datastore | Bigtable              | Cloud Storage | Cloud SQL               | Cloud Spanner           | BigQuery                |
| :----------------- | :-------------- | :-------------------- | :------------ | :---------------------- | :---------------------- | :---------------------- |
| Type               | NoSQL document  | NoSQL wide column     | Blobstore     | Relational SQL for OLTP | Relational SQL for OLTP | Relational SQL for OLAP |
| Transactions       | Yes             | Single-row            | No            | Yes                     | Yes                     | No                      |
| Complex queries    | No              | No                    | No            | Yes                     | Yes                     | Yes                     |
| Capacity           | TB+             | PB+                   | PB+           | TB+                     | PB+                     | PB+                     |
| Unit Size          | 1MB/entity      | ~10MB/cell ~100MB/row | 5TB/object    | determined by DB engine | 10240 MiB/row           | 10MB/row                |

## Use cases


| Comparison/Options | Cloud Datastore                                          | Bigtable                                               | Cloud Storage                                     | Cloud SQL                             | Cloud Spanner                                   | BigQuery                                |
| :----------------- | :------------------------------------------------------- | :----------------------------------------------------- | :------------------------------------------------ | :------------------------------------ | :---------------------------------------------- | :-------------------------------------- |
| Type               | NoSQL document                                           | NoSQL wide column                                      | Blobstore                                         | Relational SQL for OLTP               | Relational SQL for OLTP                         | Relational SQL for OLAP                 |
| Best for           | Semi-structured application data, durable key-value data | "Flat" data, Heavy read/write, events, analytical data | structured and unstructured binary or object data | Web frameworks, existing applications | Large-scale database applications (>~ 2TB)      | Interactive querying, offline analytics |
| Use Cases          | Getting started, App Engine applications                 | AdTech, Financial and IoT data                         | Images, Large media files, backups                | User credentials, Customer orders     | Whenever high I/O, global consistency is needed | Data warehousing                        |