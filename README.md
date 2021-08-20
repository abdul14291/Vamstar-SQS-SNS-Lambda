<!-- Steps:- 
1. we will create s3 bucket using S3-Bucket.YAML file with versioning Enabled and StorageClass select.
2. Using SQS-N-SNS-Lambda.YAML we will create one SQS, SNS with subscription enabled and also we will create one lambda function with SQS event and while create we add python code to push code into S3 -->