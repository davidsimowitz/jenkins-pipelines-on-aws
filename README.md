Jenkins Pipelines on AWS
========================


Udacity - Cloud DevOps Engineer Nanodegree
------------------------------------------
Build CI/CD Pipelines, Monitoring & Logging Project: Jenkins Pipelines on AWS

In this project, you will build on the skills acquired during this course. You will create and run an instance on AWS, configure Jenkins, and create a pipeline to deploy a static website on S3.


GitHub Repository Link
======================
+ [GitHub Repo used in pipeline.](https://github.com/davidsimowitz/static)
  * https://github.com/davidsimowitz/static


Configuration
==============


Set up group policies and create user
-------------------------------------

![IAM User Permissions](https://github.com/davidsimowitz/jenkins-pipelines-on-aws/blob/master/screenshot-01.png)


Launch an Ubuntu 18.04 t2.micro instance in AWS EC2 (accessible via SSH)
------------------------------------------------------------------------

![EC2 Instance](https://github.com/davidsimowitz/jenkins-pipelines-on-aws/blob/master/screenshot-02.png)


Jenkins installed and logged into for the first time
----------------------------------------------------
![Jenkins initial run on server](https://github.com/davidsimowitz/jenkins-pipelines-on-aws/blob/master/screenshot-03.png)


Logged into Blue Ocean after installing plugin
----------------------------------------------
![Logged into Blue Ocean after installing plugin](https://github.com/davidsimowitz/jenkins-pipelines-on-aws/blob/master/screenshot-04.png)


Create pipeline from GitHub repository
--------------------------------------
![Create pipeline from GitHub repository](https://github.com/davidsimowitz/jenkins-pipelines-on-aws/blob/master/screenshot-05.png)


Set up pipeline to upload to S3 bucket static website
-----------------------------------------------------
![S3 bucket static website](https://github.com/davidsimowitz/jenkins-pipelines-on-aws/blob/master/screenshot-06.png)


Add HTML linter stage in pipeline
---------------------------------
![Build fails at linting step](https://github.com/davidsimowitz/jenkins-pipelines-on-aws/blob/master/screenshot-07.png)

Correct invalid HTML tag to pass build
--------------------------------------
![Build passes after correcting invalid HTML tag](https://github.com/davidsimowitz/jenkins-pipelines-on-aws/blob/master/screenshot-08.png)
