---
layout: post
title: Deploying via Cloud 66
category: Deploying your application
---

[Cloud 66](https://www.cloud66.com) makes it easy to provision, deploy and
manage your applications on any cloud. Semaphore has native
integration for deployment through Cloud 66.

Make sure your stack is deployed with Cloud 66. Learn more about [deploying
Rails stacks with Cloud 66](https://cloud66-help.helpscoutdocs.com/article/129-rails-stacks).

To get started, find your desired project and follow "Set Up Deployment" link
under list of the branches.

<img src="/docs/assets/img/cloud66-integration/set-up-deployment.png" alt="Set Up Deployment" class="img-responsive img-bordered">

Select Cloud 66 from the list of Deployment Methods and choose Automatic.

<img src="/docs/assets/img/deployment-method.png" alt="Deployment Method" class="img-responsive img-bordered">

<img src="/docs/assets/img/cloud66-integration/deployment-strategy.png" alt="Deployment Strategy" class="img-responsive img-bordered">

You will be redirected to your Cloud 66 account and asked if you give Semaphore
permission to deploy your stacks on your behalf.

<img src="/docs/assets/img/cloud66-integration/oauth_access_rights.png" alt="OAuth Access Rights" class="img-responsive img-bordered">

Select the project you would like to deploy once the tests are successful.

__Done!__

Note that while Semaphore tracks every deploy in the project timeline, it sends
a blank request to Cloud66 to perform the actual deployment work. If it fails
for some reason, Cloud 66 will inform you.
