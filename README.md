# Evaluating Performance of Dedicated Log Volume (DLV) by Amazon RDS for PostgreSQL
This repository contains a script that leverages `pgbench` to demonstrate the performance benefits of Dedicated Log Volume (DLV) by Amazon RDS for PostgreSQL environment.

# What is DLV?
A dedicated log volume (DLV) enhances PostgreSQL performance on Amazon RDS by offloading transaction logs (WAL segments) to a separate storage volume. This segregation of transaction logs and persistent data streamlines write operations, proving especially beneficial for high IOPS workloads, or latency-sensitive applications.

Check [Using a dedicated log volume (DLV)](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_PIOPS.StorageTypes.html#USER_PIOPS.dlv) for more information.
