---
title: "Prerequisites"
date: 2020-10-29T09:44:46+02:00
weight: 1
---
### As a member of the Ops platform tools team at Gourmet Inc, you will automatically deploy and configure Jenkins using CloudShell Colony.

__Note__: This step would typically be performed ahead of time. CloudShell Colony can be used to deploy platform tools and keep them up to date with the latest version.

Complete information about this setup is available in the [Readme](https://github.com/QualiSystemsLab/jenkins-colony/blob/master/README.md) file of the Github repository. 

* Create a new Ops-tools space in Colony
* Connect your AWS account and S3 bucket artifact repository to the Ops-tools space
* Connect the Jenkins blueprint repository to Colony
* Create a IAM role that will have permission to write to your S3 bucket
* Link your artifact repo to Colony
* Generate a token for Jenkins integration with Colony
* Deploy Jenkins from Colony