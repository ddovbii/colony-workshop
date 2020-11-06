---
title: "Create an S3 role using a Cloud Formation template"
date: 2020-10-16T14:20:28+03:00
weight: 27
draft: false
---
In the next few steps, you will create an S3 role that will give Jenkins write permission to upload the promotion manager application build to the artifact repository. The role value will be used as an input to the Jenkins Sandbox deployment.

Navigate to Services: Cloud Formation to Create Stack
![27_page](/images/module3/27_page.png)
Upload template file s3_bucket_access.template provided in the workshop Git repo (jenkins directory)
![27_page](/images/module3/28_page.png)
Enter a name for the stack and specify the S3 bucket name as input parameter 
![27_page](/images/module3/29_page.png)
Follow the Next screens until you get to the stack creation button (check box at the bottom)
![27_page](/images/module3/30_page.png)
S3 role is now created. Save the value. This role will be an input of your Jenkins sandbox 
![27_page](/images/module3/31_page.png)