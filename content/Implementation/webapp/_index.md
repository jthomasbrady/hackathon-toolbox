---
title: "Build a Web Application"
weight: 1
---

![WebApp image](/images/007-display.png?width=20%)
## Build a Web Application 

```
The Amplify Command Line Interface (CLI) is a unified toolchain to create and manage your serverless infrastructure on AWS.

```

## 1. Getting set up

### Set up the command line

1. The steps below assume you have created an aws account. If you don't have one or haven't been given one for this hackathon create one <a href="https://portal.aws.amazon.com/billing/signup?redirect_url=https%3A%2F%2Faws.amazon.com%2Fregistration-confirmation" target="_blank">here</a>.

2. Install the AWS CLI on your local machine using the steps <a href = "https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html" target="_blank">here</a>
   
2. Configure the AWS CLI with Credentials as shown <a href = "https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html" target="_blank">here</a>
```
$ aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: us-west-2 // put in your region
Default output format [None]: json
```

### Set up an IDE (optional)

Optionally, you can set up and IDE to work with your AWS Environment

| AWS Cloud9                                                         | IntelliJ                                                             | VS Code                                                                      |
| ------------------------------------------------------------------ | -------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| ![Cloud9 image](/images/Cloud9Logo.png?width=90px)                 | ![IntelliJ image](/images/IntelliJ_IDEA_Logo.png?width=90px)         | ![VSCode image](/images/VSCodeLogo.png?width=90px)                           |
| <a href="https://aws.amazon.com/cloud9/" target="_blank">Setup</a> | <a href="https://aws.amazon.com/intellij/" target="_blank">Setup</a> | <a href="https://aws.amazon.com/visualstudiocode/" target="_blank">Setup</a> |


## 2. Start Building

Below are mentioned some of the ways you can quickly get a web page running in aws to start having a play with. These tools and tutorials will create a boilerplate framework and code for you so that you can start tweaking your site according to your needs.

### Build and host a Static Website on S3
```
If you want to create a simple HTML, CSS, JavaScript static site and put it up in the cloud the easiest way to do so is to host it on s3.
```
> - Use a rapid prototyping framework such as <a href="https://gohugo.io/" target="_blank">HUGO</a>. Hugo is one of the most popular open-source static site generators.
> - Use this <a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/HostingWebsiteOnS3Setup.html" target="_blank">tutorial</a> here to build and deploy a static website to s3

### Build using the Amplify Framework
```
An opinionated, category-based client framework for building scalable mobile and web apps
The Amplify Command Line Interface (CLI) is a unified toolchain to create, integrate, and manage the AWS cloud services for your app.
```
> - Install the <a href ="https://aws-amplify.github.io/docs/" target="_blank">AWS Amplify</a> CLI 
- Follow the aws amplify getting started <a href="https://aws-amplify.github.io/docs/js/start?ref=amplify-js-btn&platform=purejs" target="_blank">guide</a> to create a basic ReactJS app running in the cloud

### Build using Elastic Beanstalk 
```
Elastic Beanstalk supports applications developed in Go, Java, .NET, Node.js, PHP, Python, and Ruby. When you deploy your application, Elastic Beanstalk builds the selected supported platform version and provisions one or more AWS resources, such as Amazon EC2 instances, to run your application. 
```

> - Install the EB CLI as shown <a href="https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install.html" target="_blank">here</a>
> - Configure the EB CLI as shown <a href="https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-configuration.html" target ="_blank">here</a>


### Build using Amazon Lightsail
```
Lightsail is an easy-to-use cloud platform that offers you everything needed to build an application or website, plus a cost-effective, monthly plan. Whether you’re new to the cloud or looking to get on the cloud quickly with AWS infrastructure you trust, we’ve got you covered.
```
> - If you want to use light sail to get started with building a wordpress site use this <a href="https://lightsail.aws.amazon.com/ls/docs/en_us/articles/amazon-lightsail-tutorial-launching-and-configuring-wordpress">tutorial</a>





