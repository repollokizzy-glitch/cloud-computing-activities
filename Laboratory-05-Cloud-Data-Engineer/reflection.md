# Mission 5 Reflection

Object storage is better suited for storing millions of photos because it is designed to handle large amounts of unstructured data such as images, videos, documents, and backups. Instead of organizing data like a traditional hard drive, object storage keeps each file as an object with metadata and a unique identifier. This makes it easier to manage a very large number of files and allows storage capacity to grow as more photos are uploaded.

Docker made it easier to deploy the MinIO storage server because the application could be run inside a container without manually installing and configuring every required component. The Docker command allowed me to configure the ports, container name, administrator username, and password in one deployment command. This made the deployment process more organized and repeatable.

A bucket is a logical container used to organize objects in an object storage system. In this activity, the bucket named `client-photos` is used as the location for the sample uploaded file. Buckets help separate and organize different groups of stored objects.

Large enterprise companies can protect object storage data from physical server failures by using redundancy, replication, backups, and distributed storage systems. Multiple copies of data can be stored across different servers or locations. Disaster recovery procedures can also be used to restore information when hardware fails.

My confidence in using the Linux command line is gradually improving. At the beginning, Docker and Linux commands were unfamiliar to me, but practicing commands helped me understand how they work. I learned how to check containers, view logs, work with files, and troubleshoot errors. This activity helped me become more comfortable using the command line to manage cloud-related services.
