# CC4843-Assignment1

Uploaded necessary files for the website to function. In AWS, the files are located in a public s3 bucket that utilizes Cloudfront for additional security, lower latency, and higher transfer speeds. The following entries will hold more technical elements. Posted here at the top will be the link for the site [https://dwt2ikz0e4prq.cloudfront.net].

# Amazon s3

The s3 bucket is publically accessible and has the necessary files for the website to function. Every page an HTML file. As a backup, static website hosting is also enabled, that link for the site can be acessed from here [http://jalyn-2022-cc-website.s3-website.us-east-2.amazonaws.com]. 

# IAM
An IAM policy has been applied to the admin user group to allow access to this s3 bucket.

# Cloudfront

Cloudfront has been utilized for the aforementioned reasons. OAI has been applied to ensure additional security. It supports HTTP protocols.

# The HTML Pages

Each page has a navigation selection at the top. Once a page is selected, the previous selection becomes bolded and unselectable to denote what page was accessed. There are only images for the other pages except for the home page. The home page has a video on it as well as an image.
