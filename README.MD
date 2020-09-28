# Deploy Static Website on AWS

<h2>Project Overview</h2>

<p>In this project, we will deploy a static website to AWS using S3, CloudFront, and IAM.</p>

<p>The files included are:</p> 

<h3>index.html - The Index document for the website.</h3>
<h3>/img - The background image file for the website.</h3>
<h3>/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.</h3>
<h3>/css - CSS files for the website.</h3>

<h3>Other folders not in cloud</h3>
<h3>/screenshots</h3>

1. The S3 bucket is created.
links to img: screenshots\s3-bucket-created.JPG

2. Files upload to S3 bucket
links to img: screenshots\files-upload-toS3.JPG

3. The S3 bucket is configured to support static website hosting.
links to img: screenshots\static-website-hosting.JPG

4.The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.
links to img: screenshots\iam-bucket-policy.JPG

5. CloudFront web-distribution
links to img: screenshots\cloudfront-distribution.JPG

6.Cloudfront url endpoint: http://d38fva6swlmema.cloudfront.net/index.html


