# blog
Personal Website
My website focused on Mathematics/Statistics/Spatial and some Economics.

Github actions build job then syncs to hosted s3 bucket. Depending on ymml the static website is configured and built before uploading it to S3. Our final step is then running aws s3 sync via the AWS CLI to sync our deployed_files folder to S3 bucket. 

Website endpoint - is a static site hosted authorising public access via 'get' only ACL.
http://messanalytics.org/