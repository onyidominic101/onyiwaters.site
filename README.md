# S3 Static Website Hosting with Route 53

This project involved creating an S3 static website and configuring DNS routing with Route 53.

# Project Summary

The goals were to:

- Create an S3 bucket and configure it for static website hosting
- Upload index.html. styles.css and script.js files
- Make the S3 bucket content publicly accessible
- Register a domain and create a hosted zone with Route 53
- Create an A record to route traffic to the S3 endpoint
- Create an alias record for S3 website endpoint
- Compare A record vs alias record for routing

# Process
- Created S3 bucket "onyiwaters.site"
- Enabled static website hosting and set index.html as default
- Added bucket policy to allow public reads
- Uploaded index.html, styles.css, script.js and .webp files
- Registered onyiwaters.site domain
- Created a hosted zone in Route 53
- Added an A record pointing to S3 endpoint
- Added an alias record using the S3 website endpoint
- Tested accessing site via S3 URL and domain name

See full step-by-step process with screenshots in water-docs.md

# Code Samples
See code samples for:
- index.html (/code/index.html)
- styles.css (/code/styles.css)
- script.js (/code/script.js)
- s3-bucket-policy.json (/code/s3-bucket-policy.json)

# Learnings
- Learned S3 static website hosting options
- Practiced configuring DNS records in Route 53
- Compared A record vs alias record for routing to S3
- Implemented IAM bucket policy for public access

# Skills Demonstrated
- S3 static website hosting
- DNS management with Route 53
- IAM policies

# Site Access
The S3 static site can be accessed at http://onyiwaters.site.s3-website.us-east-2.amazonaws.com

# Enhancements
Future enhancements could include:
- Adding a custom domain and SSL certificate
- Integrating a CI/CD pipeline for deployments
- Adding a backend API

