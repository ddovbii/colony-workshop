---
title: "Deploy a sandbox from Jenkins."
date: 2020-10-16T14:20:29+03:00
weight: 39
draft: false
---

* Specify S3 artifact repo (as a parameter to Jenkins config). This is the repository that was configured in Module 1
* Run the Jenkins Job:
    * Deploy latest version of promotion app
    * Retrieve environment details (URL end point) and outputs it to the console to feed it to a test (test is a placeholder step).
    * Terminate the sandbox
* More info:
    * https://quali.atlassian.net/wiki/spaces/BD/pages/809500683/Jenkins+solution+for+Colony
    * https://quali.atlassian.net/wiki/spaces/BD/pages/875036714/How+to+handle+artifacts 