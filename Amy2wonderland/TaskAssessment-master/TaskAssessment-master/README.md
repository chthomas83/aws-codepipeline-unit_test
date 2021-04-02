# Website - Task Assessment 
secure serverless-website----


#Local Repo-->GithubRepo-->CodePipeline-->S3-->CloudFront


#Cretate branch in GitHub and push to CI/CD through Webhook- Version Control=====

#Source Files need to be put into this repo from local branch repo====

#Docker Container can be build and pushed from GitHub

#Cognito.yaml--> If the website is internal and not public

#rds.yaml--> Create sepearte RDS SQL instancefor backend tier

#Run template as nested stacks by:
upload rds.yaml and cognito.yaml to S3 bucket and Ref in parent template (This is optional)

