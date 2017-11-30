# duduksini-s3
In order to run duduksini's stack in AWS, we need an s3 bucket to store duduksini's lambda artifacts, database backups, and static files.  
If we run the stack locally, this is not necessary.

## Deploying to AWS S3
1. Make sure aws cli is configured with access and secret key
2. Run deploy.sh inside `/aws` folder
