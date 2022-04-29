# seccamdb

Mutable Database backend for SeccamProject

Warning! current dockerfile is set to be mutable. All data should be stored on another mount point if you want it to be immutable via AWS EFS or S3

Docker build -t <buildname:tag> --build-arg DEFINED_PASSWORD=”mysqlpassword” --build-arg DEFINED_DBNAME = “seccam_db”

Deploy this into any container via podman, docker, or via Kubernetes orchestration.

Our demo is hosted on on EKS in AWS.
