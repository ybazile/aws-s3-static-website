# Hosting a Static Website on Amazon S3

## Project Overview
In this project, I deployed a static HTML/CSS website using Amazon S3. I created an S3 bucket, configured it for static website hosting, applied the correct permissions, and made the site publicly accessible. This project helped me understand core AWS fundamentals such as cloud storage, access control, bucket policies, and static hosting.

http://yvener-cloud-portfolio.s3-website-us-east-1.amazonaws.com

## What I Built
- A fully hosted static website on Amazon S3
- A custom 404 error page
- Public access configuration using bucket policies
- A simple cloud-based deployment workflow

## Tools and Services Used
- Amazon S3 for storage and static hosting
- AWS Management Console for configuration
- HTML and CSS for the website content
- IAM and bucket policies for access control

## Key Concepts Learned
- How S3 stores and serves static files
- How to configure a bucket for website hosting
- How public access and bucket policies work
- How to troubleshoot 403 Forbidden errors
- How to create and configure a custom 404 page

## Steps Completed
1. Created a new S3 bucket with a globally unique name  
2. Uploaded HTML and CSS files  
3. Enabled static website hosting  
4. Set `index.html` as the default document  
5. Added `404.html` as the error document  
6. Configured bucket policies to allow public read access  
7. Tested the website endpoint  

## Time and Challenges
This project took approximately 30 minutes to complete.  
The most challenging part was understanding how S3 permissions and bucket policies work when making the bucket public.

## Next Steps
I completed this project to build a foundation in cloud fundamentals. My next goal is to learn more about IAM security best practices, VPC networking, and AWS security services such as CloudTrail and GuardDuty.
