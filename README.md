# aws-localstack-windows

1. Install and Start Docker Desktop on Windows
2. docker run --rm -it -p 4566:4566 -p 4571:4571 localstack/localstack
3. Open Windows Powershell
4. Run pip install awscli-local
5. awslocal s3api list-buckets --region us-east-1

curl http://localhost:4566/health

![image](https://github.com/srss-pocs/aws-localstack-windows/assets/145287517/f94a394d-ce00-4a60-ae89-19da7063c426)
