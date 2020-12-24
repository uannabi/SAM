Resources needed in your AWS account before beginning the demos:
1. An S3 bucket
    - You can find an example of the bucket policy in the Permissions folder
2. IAM Roles for the lambda functions
    - Policies to attach
        - LambdaBasicExecutionRole
        - AWSXrayFullAccess
        - AmazonSSMFullAccess or more tightly scoped custom policy
        - AmazonS3FullAccess or more tightly scoped custom policy
3. Parameters in AWS Systems Manager Parameter Store
    - One parameter for the bucket name, unencrypted
        -  Use dragon_data_bucket_name for the name of the parameter
    - One parameter for the key name, unencrypted
        - Use dragon_data_file_name for the name of the parameter
        
4. Use Steps functions

5. Payload and all permission perameter . 

