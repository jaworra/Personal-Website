# Personal Website template
A simple page template suited for personal and portfolio pages. 
With research interest in Mathematics, applied probablity and computational statistics.

### CI/CD via github actions
Github actions for integarations and delivery to AWS resourcest. Depending on yml spec the static website is configured and built priot to  final step of running aws s3 sync via the AWS CLI from 'deployed_files' folder to S3 bucket 'messanalytics.org'. 


### Endpoint 
Website endpoint - is a static site hosted authorising public access via 'get' only ACL.
http://messanalytics.org/

### Dependencies
javascript (d3 vers4) for banners.
github actions (aws cli) for syncing.
