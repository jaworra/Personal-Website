# personal website template

A simple page template suited for personal and portfolio pages. 
With research interest in Mathematics, applied probablity and computational statistics.


## ci/cd with github actions

Github actions build job then syncs to hosted s3 bucket. Depending on ymml the static website is configured and built before uploading it to S3. Our final step is then running aws s3 sync via the AWS CLI to sync our deployed_files folder to S3 bucket. 


## endpoint 

Website endpoint - is a static site hosted authorising public access via 'get' only ACL.
http://messanalytics.org/
