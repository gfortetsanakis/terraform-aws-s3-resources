## Terraform module for S3 bucket

This modules creates a new S3 bucket on AWS.

## Module input parameters

| Parameter   | Description                                                                                                |
| ----------- | ------------------------------------------- |
| bucket_name | The name of the bucket to be created        |
| bucket_tag  | A short tag used to identify the new bucket |


## Module output parameters

| Parameter            | Description                      |
| -------------------- | -------------------------------- |
| bucket_name          | The name of the created bucket   |