Project Title: Deploy Static Website on AWS

Project Objective: Deploy a static website on AWS to leverage the cloud's ability to host static websites that only include HTML, CSS, and Javascript files that require no server-side processing.

Project Methodology: 

Step 1: Create an S3 bucket, configure the bucket for web hosting, and secure it using IAM policies. 
Step 2: Upload the website files to the S3 bucket and speed up content delivery using CloudFront.
Step 3: Access the static website in the Google Chrome browser using the unique S3 endpoint.


Project Result: The static website was deployed to AWS using S3, CloudFront, and IAM; using the following files: 

a: index.html - The Index document for the website.
b: /img - The background image file for the website.
c: /vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
d: /css - CSS files for the website.

The required screenshots are included, all required functionality exists, and the project behaves as expected per the project's specifications.

The CloudFront enpoint URL for this project is: http://mywinningbucket.s3-website-us-east-1.amazonaws.com/.

