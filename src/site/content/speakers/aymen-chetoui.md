---
title: "Leveraging Serverless to meet infrastructure SLAs"
description: "Rolling out infrastructure updates can be a daunting task, especially if there are hard SLAs to be met, f.eg. in terms of security patches.
In large complex and cross-team production environments, the readiness of newly bootstrapped servers is often taken for granted, until the sad day when things stop working. Then long hours and sometimes days are spent debugging recent configuration changes, which could date back to days even weeks, especially if rotating servers is a seldom and manual procedure.
In this talk, we will explain how we have managed to periodically and automatically, test and then confidently apply infrastructure configuration changes, even on datastore clusters, such as Elasticsearch.
With a minimum cost, we have built a tool that is helping us periodically rollout security patches on over 100 servers every second week. It has reduced the time to fix configuration issues. And furthermore, it has increased our trust in the readiness of our production infrastructure through an automated pipeline, instead of regular painful manual interventions. We call it the Instance Recycler.
The Instance Recycler uses the Serverless Framework and leverages among others actions triggered from AWS Lambda Functions and pipelines organised with AWS Step Functions."
speaker: Aymen Chetoui
bio: "After a consulting role and a startup experience as a DevOps Engineer, I have joined the Zendesk Guide product at the Copenhagen office. I have been part of the Product Operations team for almost two years now. Where we have faced many challenges and had to come up with innovative solutions to best serve our clients and assist our fellow developers.
I have also been an AWS Certified Solutions Architect for the past two years and am now undertaking the certificate renewal exam. This has kept my hands-on expertise with AWS Serverless solutions up-to-date. Sharing the knowledge I have aquired, is a part of my daily job, especially with Launch and Learn and weekly Intro Sessions to AWS, that I have been organising at our office.
I am a strong adept of Automation and Infrastructure As a Code, to reach Reliability requirements and Security SLAs. And given both the opportunity and the challenge, writing Serverless scripts is a second nature in my mission."
image: /images/speakers/Aymen_Chetoui.jpg
---