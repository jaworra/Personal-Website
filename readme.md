# Personal Website template
Personal, portfolio and blog website with theme inspired Mathematics, applied probablity and computational statistics.

### CI/CD, CI-github actions, CD-aws 
Github actions for integarations and delivery to AWS resources. Depending on yml spec the static website is configured and built priot to  final step of running aws s3 sync via the AWS CLI of 'deployed_files' folder to S3 bucket 'website-personal-john-worrall'. 

### Endpoint 
Website endpoint - is a static site hosted authorising public access via 'get' only ACL.
Distributed site using cloudfront which cache for high availability - needs
to invalidate endpoints to see quick changes (<24hours). 
https://messanalytics.org/ or https://johnworrall.com.au/ 


### Dependencies
javascript (d3 vers4) for banners.
github actions (aws cli) for syncing.
