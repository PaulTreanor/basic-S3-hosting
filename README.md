# Basic S3 hosting with the Serverless Framework 

Made for future reference. No domains, literally just a bucket with distribution files in it. Useful for letting peopel get their hands on a quick prototype without any overhead. 

# How to use 
*This requires you to have the serverless framework installed (`npm install -g serverless`) and to have AWS environment variables for your account set up.*

1. Clone this git repo 
2. Put your site's files in /static 
3. Set your region in serverless.yml
4. Set your siteName in serverless.yml (it must be unique because it's an S3 bucket)
5. Run `npm install`
5. run `serverless deploy`


# Link to deployed website 
http://serverless-static-site-paul.s3-website-eu-west-1.amazonaws.com/

# Deployed website link format 

http://bucket-name.s3-website-Region.amazonaws.com or http://bucket-name.s3-website.Region.amazonaws.com

