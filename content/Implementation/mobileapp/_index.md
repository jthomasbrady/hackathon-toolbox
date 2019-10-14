---
title: "Build a Mobile Application"
weight: 5
---
![TAT image](/images/009-sync.png?width=20%)

## Build a Mobile Application
```
A mobile application is to be downloaded an run on an ios or android mobile device
```
### Getting set up

1. Install the AWS CLI using the steps <a href = "https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html">here</a>
   
2. Configure the aws CLI with Credentials as shown <a href = "https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html" target="_blank">here</a>
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

### Start Building

1. Install the aws amplify cli 
```
$ npm install -g @aws-amplify/cli
$ amplify configure
```

2. Familiarise yourself with the amplify CLI commands by having a quick glance at this <a href="https://aws-amplify.github.io/docs/cli-toolchain/quickstart?sdk=js">CheatSheet</a> 