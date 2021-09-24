# Basic S3 hosting with the Serverless Framework 

Made for future reference. No domains, literally just a bucket with distribution files in it. Useful for letting peopel get their hands on a quick prototype without any overhead. 

# How to use 
1. Put website files in /static
2. Edit details in serverless.yml
3. Remember that the bucket name (custom siteName) must be unique
4. Install the serverless framework and run `npm install`
5. run `serverless deploy`


# Link to deployed website 
http://serverless-static-site-paul.s3-website-eu-west-1.amazonaws.com/

# Deployed website link format 

http://bucket-name.s3-website-Region.amazonaws.com
  
  or 
  
http://bucket-name.s3-website.Region.amazonaws.com

