# iac-terraform-hybrid-cloud

aws lambda invoke --region=us-east-1 --function-name=ServerlessExample output.txt

aws s3api create-bucket --bucket=terraform-serverless-example --region=us-east-1

aws s3 cp example.zip s3://terraform-serverless-example/v1.0.0/example.zip

zip ../example.zip main.js


