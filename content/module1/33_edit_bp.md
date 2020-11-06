---
title: "Edit the promotion-manager-dev blueprint​"
date: 2020-10-15T18:47:14+03:00
weight: 33
draft: false
---
1\. Edit promotion-manager-dev.yaml. You can find this file in the Git directory of your repo:
aws-workshop-colony/blueprints/

![43_page](/images/module1/edit_bp_git.png)
__Note__: this blueprint assumes you have permissions to deploy in “eu-west-1” region with your AWS account, if not update the value in the clouds section.

![43_page](/images/module1/pm_bp_view.png)

2\. For each application tier, uncomment #target: vm1​
![44_page](/images/module1/44_page.png)

3\. Commit your changes (Git)
![45_page](/images/module1/45_page.png)

