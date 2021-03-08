# CodingChallenge
CodingChallengeCultureAmp

This template defines an S3 bucket,Cloudfront,Cloudfront Origin Access Identity and Lambda to build a web application. The Cloudfront is used for serving content globally
as well as caching objects

The S3 stores the files and whenver a user uploads a file to the bucket, a Lambda Fuction is triggered. This trigger gives a response back detailing whether the upload was successful
