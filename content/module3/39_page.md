---
title: "Deploy the promotion manager application from Jenkins."
date: 2020-10-16T14:20:29+03:00
weight: 39
draft: false
---

Your newly deployed Jenkins server is already preconfigured to run the promotion manager application. 

2\. Run the Jenkins Job. This job will:
    * Retrieve the latest version of your promotion from the Git repo.
	* Create a build with the latest version of promotion app and upload it to your artifact repository.
	* Deploy latest version of promotion app into a sandbox using Colony's REST API.
    * Retrieve environment details (URL end point), using Colony's REST API, and outputs it to the console to feed it to a test (test is a placeholder step).
    * Terminate the sandbox using Colony's REST API
 