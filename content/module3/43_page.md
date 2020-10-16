---
title: "Pipeline steps"
date: 2020-10-16T14:20:29+03:00
weight: 43
draft: false
---

#### The default pipeline loaded with this Jenkins instance will automatically run the following steps:

1. Retrieve latest code of the promotion app from Git
2. Build artifact package (latest build)
3. Upload Build to S3 repository
4. Deploy the promotion application to AWS in a Colony Sandbox
5. Run tests
6. Terminate the promotion application