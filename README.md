# aws-localstack-windows

1. Start Docker Desktop on Windows
2. docker run --rm -it -p 4566:4566 -p 4571:4571 localstack/localstack
3. Open Windows Powershell
4. Run pip install awscli-local
5. awslocal s3api list-buckets --region us-east-1
