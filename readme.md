# Personal Website template
Personal, portfolio and blog website with theme inspired Mathematics, applied probablity and computational statistics.

### CI/CD, CI-github actions, CD-aws 
Github actions for integarations and delivery to AWS resources. Depending on yml spec the static website is configured and built priot to  final step of running aws s3 sync via the AWS CLI of 'deployed_files' folder to S3 bucket 'messanalytics.org'. 

### Endpoint 
Website endpoint - is a static site hosted authorising public access via 'get' only ACL.
Distributed site using cloudfront which cache for high availability - this means will need
to invalidate endpoints to see changes. 
http://messanalytics.org/


### Dependencies
javascript (d3 vers4) for banners.
github actions (aws cli) for syncing.
