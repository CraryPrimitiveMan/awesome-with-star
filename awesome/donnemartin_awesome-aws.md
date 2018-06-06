# Information comes from [donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws)
<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/data-science-ipython-notebooks/master/images/aws.png">
</p>
<br/>

# Awesome AWS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome AWS libraries, open source repos, guides, blogs, and other resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

## The Fiery Meter of AWSome

* Repo with 0100+ Stars: :fire:
* Repo with 0200+ Stars: :fire::fire:
* Repo with 0500+ Stars: :fire::fire::fire:
* Repo with 1000+ Stars: :fire::fire::fire::fire:
* Repo with 2000+ Stars: :fire::fire::fire::fire::fire:

Repos not on `The Fiery Meter of AWSome` can still be awesome, see [A Note on Repo AWSomeness](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md#a-note-on-repo-awsomeness).

### `awesome-aws` Python Module

[![Build Status](https://travis-ci.org/donnemartin/awesome-aws.svg?branch=master)](https://travis-ci.org/donnemartin/awesome-aws) [![Codecov](https://img.shields.io/codecov/c/github/donnemartin/awesome-aws.svg)](https://codecov.io/github/donnemartin/saws/awesome-aws) [![PyPI version](https://badge.fury.io/py/awesome-aws.svg)](http://badge.fury.io/py/awesome-aws)

The Python module [`awesome-aws`](https://github.com/donnemartin/awesome-aws/tree/master/awesome) regularly scans repos on [Awesome AWS](https://github.com/donnemartin/awesome-aws) to maintain the accuracy of the `Fiery Meter of AWSome`.

## Contributing

Contributions are welcome!

Review the [Contributing Guidelines](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md).

Also check out the [Watch List](https://github.com/donnemartin/awesome-aws/issues/34).

## Index

* [SDKs and Samples](#sdks-and-samples)
    * [Android](#android-sdk)
    * [C++](#c-sdk)
    * [Clojure](#clojure-sdk)
    * [Go](#go-sdk)
    * [iOS](#ios-sdk)
    * [IoT](#iot-sdk)
    * [Java](#java-sdk)
    * [JavaScript](#javascript-sdk)
    * [Haskell](#haskell-sdk)
    * [Perl](#perl-sdk)
    * [PHP](#php-sdk)
    * [Python](#python-sdk)
    * [Ruby](#ruby-sdk)
    * [Rust](#rust-sdk)
    * [Scala](#scala-sdk)
    * [Xamarin](#xamarin-sdk)
    * [Unity](#unity-sdk)
    * [.NET](#net-sdk)
* [Command Line Tools](#command-line-tools)
    * [Universal Command Line Interface](#universal-command-line-interface)
    * [Windows PowerShell](#windows-powershell)
* [IDE Toolkits](#ide-toolkits)
    * [Eclipse Toolkit](#eclipse-toolkit)
    * [Visual Studio Toolkit](#visual-studio-toolkit)
* [Open Source Repos](#open-source-repos)
    * [API Gateway](#api-gateway)
    * [CLI](#cli)
    * [CloudFormation](#cloudformation)
    * [CloudSearch](#cloudsearch)
    * [CloudTrail](#cloudtrail)
    * [CloudWatch](#cloudwatch)
    * [Code Deploy](#code-deploy)
    * [Code Pipeline](#code-pipeline)
    * [Cognito](#cognito)
    * [Data Pipeline](#data-pipeline)
    * [Device Farm](#device-farm)
    * [DynamoDB](#dynamodb)
    * [Elastic Beanstalk](#elastic-beanstalk)
    * [Elastic Container Service](#elastic-container-service)
    * [Elastic File System](#elastic-file-system)
    * [Elastic MapReduce](#elastic-mapreduce)
    * [Elastic Search](#elastic-search)
    * [Elasticache](#elasticache)
    * [Glacier](#glacier)
    * [Kinesis](#kinesis)
    * [Lambda](#lambda)
    * [Machine Learning](#machine-learning)
    * [Mobile Analytics](#mobile-analytics)
    * [OpsWorks](#opsworks)
    * [Redshift](#redshift)
    * [Route 53](#route-53)
    * [S3](#s3)
    * [SNS](#sns)
    * [SQS](#sqs)
    * [Data](#data)
    * [DevOps](#devops)
    * [Security](#security)
    * [Accompanying](#accompanying-repos)
    * [Miscellaneous](#miscellaneous-repos)
* [Guides, Books, Documentation, and Training](#guides-books-documentation-and-training)
    * [Getting Started Guides](#getting-started-guides)
    * [General Guides](#general-guides)
    * [Books](#books)
    * [Whitepapers](#whitepapers)
    * [Documentation](#documentation)
    * [Training](#training)
    * [Case Studies: Powered by AWS](#case-studies-powered-by-aws)
* [Social](#social)
    * [Blogs](#blogs)
    * [Twitter Influencers](#twitter-influencers)
    * [Facebook Pages](#facebook-pages)
    * [YouTube Channels](#youtube-channels)
    * [LinkedIn Groups](#linkedin-groups)
    * [Subreddits](#subreddits)
    * [Conferences](#conferences)
* [Latest KPIs and Stats](#latest-kpis-and-stats)
* [Appendix of Core Services](#appendix-of-core-services)
    * [Services in Plain English](#services-in-plain-english)
    * [Compute](#compute-services)
    * [Networking](#networking-services)
    * [Enterprise Applications](#enterprise-applications)
    * [Analytics](#analytics-services)
    * [Artificial Intelligence](#artificial-intelligence)
    * [Management Tools](#management-tools)
    * [Security and Identity](#security-and-identity-services)
    * [Internet of Things](#internet-of-things-service)
    * [Mobile Services](#mobile-services)
    * [Storage and Content Delivery](#storage-and-content-delivery-services)
    * [Databases](#databases)
    * [Application Services](#application-services)
    * [Developer Tools](#developer-tools)
    * [Miscellaneous Services](#miscellaneous-services)
* [Contributing](#contributing)
* [Credits](#credits)
* [Other Awesome Lists](#other-awesome-lists)
* [Contact Info](#contact-info)
* [License](#license)

## SDKs and Samples

*AWS and community SDKs with samples and docs, grouped by language.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/TK96G8T.png">
</p>
<br/>

### Android SDK

* [Repo :fire::fire:](https://github.com/aws/aws-sdk-android) :star:472
* [Repo with Samples :fire::fire::fire:](https://github.com/awslabs/aws-sdk-android-samples) :star:609
* [Install](http://sdk-for-android.amazonwebservices.com/latest/aws-android-sdk.zip)
* [Docs](https://aws.amazon.com/documentation/sdk-for-android/)
* [Learn More](https://aws.amazon.com/mobile/sdk/)

### C++ SDK

* [Repo :fire::fire::fire:](https://github.com/awslabs/aws-sdk-cpp) :star:701
* [Blog with Samples](https://aws.amazon.com/blogs/aws/introducing-the-aws-sdk-for-c/)

*The C++ SDK is a labs project with limited docs and/or samples.*

### Clojure SDK

* [Repo :fire::fire::fire:](https://github.com/mcohen01/amazonica) :star:746
* [Install](https://github.com/mcohen01/amazonica#installation)
* [Docs](https://github.com/mcohen01/amazonica#documentation)

*The Clojure SDK is a community project with limited docs and/or samples.*)

### Go SDK

* [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-sdk-go) :star:4003
* [Install](https://github.com/aws/aws-sdk-go/wiki)
* [Docs](http://docs.aws.amazon.com/sdk-for-go/api/)
* [Learn More](https://aws.amazon.com/sdk-for-go/)

Related Repos:

* [goamz/goamz :fire::fire:](https://github.com/goamz/goamz) :star:360

### iOS SDK

* [Repo :fire::fire::fire::fire:](https://github.com/aws/aws-sdk-ios) :star:1013
* [Repo with Samples :fire::fire::fire:](https://github.com/awslabs/aws-sdk-ios-samples) :star:725
* [Install](http://sdk-for-ios.amazonwebservices.com/latest/aws-ios-sdk.zip)
* [Docs](https://aws.amazon.com/documentation/sdk-for-ios/)
* [Learn More](https://aws.amazon.com/mobile/sdk/)

### IoT SDK

* [Repo for Arduino](https://github.com/awslabs/aws-sdk-arduino) :star:81
* [Repo for C :fire::fire:](https://github.com/aws/aws-iot-device-sdk-embedded-C) :star:387
* [Repo for JavaScript :fire::fire::fire:](https://github.com/aws/aws-iot-device-sdk-js) :star:599
* [Repo for Arduino Yun :fire:](https://github.com/aws/aws-iot-device-sdk-arduino-yun/)
* [Docs](http://docs.aws.amazon.com/iot/latest/developerguide/what-is-aws-iot.html)

*The IoT SDK is a labs project with limited docs and/or samples.*

### Java SDK

* [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-sdk-java) :star:2496
* [Repo with Samples :fire:](https://github.com/awslabs/aws-java-sample) :star:150
* [Install](http://sdk-for-java.amazonwebservices.com/latest/aws-java-sdk.zip)
* [Docs](https://aws.amazon.com/documentation/sdk-for-java/)
* [Learn More](https://aws.amazon.com/sdk-for-java/)

### JavaScript SDK

* [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-sdk-js) :star:4175
* [Repo with Samples :fire::fire:](https://github.com/awslabs/aws-nodejs-sample) :star:204
* [Install](http://docs.aws.amazon.com/AWSJavaScriptSDK/guide/node-intro.html)
* [Docs](https://aws.amazon.com/documentation/sdk-for-javascript/)
* [Learn More](https://aws.amazon.com/sdk-for-node-js/)

Related Repos:

* [aws/aws-amplify :fire::fire::fire::fire::fire:](https://github.com/aws/aws-amplify) :star:2812
* [chilts/awssum :fire::fire:](https://github.com/chilts/awssum) :star:471
* [mirkokiefer/aws-lib :fire::fire::fire:](https://github.com/mirkokiefer/aws-lib) :star:693
* [SaltwaterC/aws2js :fire::fire:](https://github.com/SaltwaterC/aws2js) :star:241

### Haskell SDK

* [Repo :fire::fire:](https://github.com/brendanhay/amazonka) :star:303
* [Docs](http://brendanhay.nz/amazonka-doc/)

Related Repos:

* [aristidb/aws :fire:](https://github.com/aristidb/aws) :star:189

*The Haskell SDK is a community project with limited docs and/or samples.*

### Perl SDK

* [Repo :fire:](https://github.com/pplu/aws-sdk-perl) :star:109
* [Repo with Samples :fire:](https://github.com/pplu/aws-sdk-perl/tree/master/examples)
* [Install](https://github.com/pplu/aws-sdk-perl#installation)
* [Docs](https://metacpan.org/pod/Paws)
* [Learn More](https://metacpan.org/pod/Paws)

*The Perl SDK is a community project.*

### PHP SDK

* [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-sdk-php) :star:3175
* [Repo with Samples](https://github.com/awslabs/aws-php-sample) :star:71
* [Install](http://docs.aws.amazon.com/aws-sdk-php/v3/guide/getting-started/installation.html)
* [Docs](https://aws.amazon.com/documentation/sdk-for-php/)
* [Learn More](https://aws.amazon.com/sdk-for-php/)

Related Repos:

* [aws-sdk-php-laravel :fire::fire::fire:](https://github.com/aws/aws-sdk-php-laravel) :star:993
* [aws-sdk-php-silex](https://github.com/aws/aws-sdk-php-silex) :star:81
* [aws-sdk-php-zf2](https://github.com/aws/aws-sdk-php-zf2) :star:94

### Python SDK

* [Repo :fire::fire::fire::fire::fire:](https://github.com/boto/boto3) :star:3389
* [Repo with Samples](https://github.com/awslabs/aws-python-sample) :star:98
* [Install](http://github.com/boto/boto#installation) :star:6110
* [Docs](http://docs.pythonboto.org/en/latest/)
* [Learn More](http://github.com/boto/boto/blob/develop/README.rst#boto)

Related Repos:

* [boto3 :fire::fire::fire::fire::fire:](https://github.com/boto/boto3) :star:3389
* [botocore :fire::fire:](https://github.com/boto/botocore) :star:464

### Ruby SDK

* [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-sdk-ruby) :star:2671
* [Repo with S3 Sample](https://github.com/awslabs/aws-ruby-sample) :star:23
* [Install](http://docs.aws.amazon.com/sdk-for-ruby/v2/developer-guide/setup-install.html)
* [Docs](https://aws.amazon.com/documentation/sdk-for-ruby/)
* [Samples :fire::fire::fire:](https://github.com/awsdocs/aws-doc-sdk-examples/tree/master/ruby/example_code/)

Related Repos:

* [aws-sdk-rails :fire::fire:](https://github.com/aws/aws-sdk-rails) :star:217
* [appoxy/aws :fire::fire:](https://github.com/appoxy/aws) :star:237
* [rightscale/right_aws :fire::fire:](https://github.com/rightscale/right_aws) :star:458

### Rust SDK

* [Repo :fire::fire::fire:](https://github.com/rusoto/rusoto) :star:589
* [Install](https://github.com/rusoto/rusoto#installation)
* [Docs](https://rusoto.github.io/rusoto/rusoto/index.html)

*The Rust SDK is a community project with limited docs and/or samples.*

### Scala SDK

* [Repo](https://github.com/awslabs/aws-scala-sdk) :star:76

Related Repos:

* [atlassian/aws-scala](https://bitbucket.org/atlassian/aws-scala)
* [seratch/AWScala :fire::fire::fire:](https://github.com/seratch/AWScala) :star:580

*The Scala SDK is a labs project with limited docs and/or samples.*

### Unity SDK

* [Repo](https://github.com/aws/aws-sdk-unity) :star:96
* [Repo with Samples](https://github.com/awslabs/aws-sdk-unity-samples) :star:84
* [Install](https://s3.amazonaws.com/aws-unity-sdk/latest/aws-unity-sdk.zip)
* [Docs](http://docs.aws.amazon.com/mobile/sdkforunity/developerguide/)

### Xamarin SDK

* [Repo](https://github.com/awslabs/aws-sdk-xamarin) :star:48
* [Blog with Samples](https://blog.xamarin.com/amazon-web-services-aws-mobile-sdks-for-xamarin-now-available/)

*The Xamarin SDK is a labs project with limited docs and/or samples.*

### .NET SDK

* [Repo :fire::fire::fire:](https://github.com/aws/aws-sdk-net) :star:891
* [Repo with Samples](https://github.com/awslabs/aws-auto-scaling-console-sample) :star:15
* [Install](http://sdk-for-net.amazonwebservices.com/latest/AWSToolsAndSDKForNet.msi)
* [Docs](https://aws.amazon.com/documentation/sdk-for-net/)
* [Learn More](https://aws.amazon.com/sdk-for-net/)
* [Samples :fire:](https://github.com/awslabs/aws-sdk-net-samples) :star:102

## Command Line Tools

*AWS and community command line tools with samples and docs.*

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/data-science-ipython-notebooks/master/images/commands.png">
</p>
<br/>

### Universal Command Line Interface

* [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-cli) :star:6496
* [Install](http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-set-up.html)
* [Docs](https://aws.amazon.com/documentation/cli/)
* [Learn More](https://aws.amazon.com/cli/)

Related Repos:

* [awslabs/aws-shell :fire::fire::fire::fire::fire:](https://github.com/awslabs/aws-shell) :star:3902
* [donnemartin/saws :fire::fire::fire::fire::fire:](https://github.com/donnemartin/saws) :star:3617

### Windows PowerShell

* [Install](http://sdk-for-net.amazonwebservices.com/latest/AWSToolsAndSDKForNet.msi)
* [Docs](https://aws.amazon.com/documentation/powershell/)
* [Learn More](https://aws.amazon.com/powershell/)

## IDE Toolkits

*Official IDE toolkits with samples and docs.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/x4nu914.png">
</p>
<br/>

### Eclipse Toolkit

* [Install](http://docs.aws.amazon.com/AWSToolkitEclipse/latest/ug/tke_setup.html)
* [Docs](https://aws.amazon.com/documentation/awstoolkiteclipse/)
* [Learn More](https://aws.amazon.com/eclipse/)

### Visual Studio Toolkit

* [Install](http://sdk-for-net.amazonwebservices.com/latest/AWSToolsAndSDKForNet.msi)
* [Docs](https://aws.amazon.com/documentation/aws-toolkit-visual-studio/)
* [Learn More](https://aws.amazon.com/visualstudio/)

## Open Source Repos

*AWS and community open source projects, grouped by service.  See [A Note on Repo AWSomeness](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md#a-note-on-repo-awsomeness) for more details.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/wbhTgga.png">
</p>
<br/>

### API Gateway

AWS Repos:

* [api-gateway-secure-pet-store :fire::fire:](https://github.com/awslabs/api-gateway-secure-pet-store) - Cognito credentials through Lambda. :star:264
* [aws-apigateway-sdk-java](https://github.com/awslabs/aws-apigateway-sdk-java) - SDK for Java. :star:19
* [aws-apigateway-swagger-importer :fire::fire:](https://github.com/awslabs/aws-apigateway-importer) - Tools to work with Swagger. :star:495

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### CLI

AWS Repos:

* [awscli-aliases :fire:](https://github.com/awslabs/awscli-aliases) - Repository for AWS CLI aliases. :star:187
* [amazon-ecs-cli :fire::fire::fire:](https://github.com/aws/amazon-ecs-cli) - ECS CLI using the same Docker Compose file format and familiar Compose commands. :star:922
* [aws-cli :fire::fire::fire::fire::fire:](https://github.com/aws/aws-cli) - Universal Command Line Interface. :star:6496
* [aws-shell :fire::fire::fire::fire::fire:](https://github.com/awslabs/aws-shell) :star:3902
* [awscli-cookbook](https://github.com/awslabs/awscli-cookbook) - Installs the CLI tools and provides a set of LWRPs for use within chef cookbooks. :star:36
* [awsmobile-cli](https://github.com/aws/awsmobile-cli) - CLI experience for Frontend developers in the JavaScript ecosystem. :star:83

Community Repos:

* [achiku/jungle :fire::fire::fire:](https://github.com/achiku/jungle) - Operations by EC2 and ELB cli should be simpler. :star:838
* [donnemartin/saws :fire::fire::fire::fire::fire:](https://github.com/donnemartin/saws) - A Supercharged AWS Command Line Interface. :star:3617
* [timkay/aws :fire::fire:](https://github.com/timkay/aws) - Easy command line access to Amazon EC2, S3, SQS, ELB, and SDB. :star:361
* [wallix/awless :fire::fire::fire::fire::fire:](https://github.com/wallix/awless) - a Powerful CLI for EC2, IAM and S3 in Go. :star:3709
* [99designs/aws-vault :fire::fire::fire::fire:](https://github.com/99designs/aws-vault) - A tool for securely storing AWS credentials, written in Go. :star:1239

### CloudFormation

AWS Repos:

* [aws-cfn-custom-resource-examples](https://github.com/awslabs/aws-cfn-custom-resource-examples) - Custom resource examples. :star:58
* [aws-cfn-resource-bridge](https://github.com/aws/aws-cfn-resource-bridge) - Custom resource framework. :star:70
* [cfncluster-cookbook](https://github.com/awslabs/cfncluster-cookbook) - Sample Cookbook. :star:31
* [cfncluster :fire::fire:](https://github.com/awslabs/cfncluster) - Framework that deploys and maintains HPC clusters. :star:276

Community Repos:

* [Appliscale/perun](https://github.com/Appliscale/perun) - A CLI tool for linting/validation and managing CloudFormation templates and stacks. :star:55
* [bazaarvoice/cloudformation-ruby-dsl :fire:](https://github.com/bazaarvoice/cloudformation-ruby-dsl) - Ruby DSL for creating templates. :star:187
* [beaknit/cform](https://github.com/beaknit/cform) - SublimeText plugin. :star:88
* [cloudreach/sceptre] :fire::fire:](https://github.com/cloudreach/sceptre) - A CLI tool for automating CloudFormation. :star:495
* [cloudtools/troposphere :fire::fire::fire::fire::fire:](https://github.com/cloudtools/troposphere) - Python library to create descriptions. :star:2770
* [peterkh/cumulus :fire::fire:](https://github.com/peterkh/cumulus) - Manages stacks. :star:201
* [envato/stack_master :fire:](https://github.com/envato/stack_master) - A CLI tool to manage CloudFormation stacks. :star:173
* [sparkleformation/sfn](https://github.com/sparkleformation/sfn) - CLI for stack management. :star:49
* [sparkleformation/sparkle_formation :fire:](https://github.com/sparkleformation/sparkle_formation) - Ruby DSL for template creation. :star:180

### CloudSearch

AWS Repos:

* [cloudsearchable](https://github.com/awslabs/cloudsearchable) - An ActiveRecord-style ORM query interface. :star:42

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### CloudTrail

AWS Repos:

* [aws-cloudtrail-processing-library](https://github.com/aws/aws-cloudtrail-processing-library) - Easily consume and process log files. :star:56

Community Repos:

* [AppliedTrust/traildash :fire::fire:](https://github.com/AppliedTrust/traildash) - Slick dashboard. :star:350

### CloudWatch

AWS Repos:

* [cloudwatch-logs-subscription-consumer :fire::fire:](https://github.com/awslabs/cloudwatch-logs-subscription-consumer) - Kinesis stream reader. :star:357
* [ecs-cloudwatch-logs](https://github.com/awslabs/ecs-cloudwatch-logs) - Assets in the blog post on using Amazon ECS and Amazon CloudWatch logs. :star:60
* [logstash-output-cloudwatchlogs](https://github.com/awslabs/logstash-output-cloudwatchlogs) - A logstash plugin that sends logs to CloudWatch. :star:32
* [opsworks-cloudwatch-logs-cookbooks](https://github.com/awslabs/opsworks-cloudwatch-logs-cookbooks) - OpsWorks sample cookbook. :star:7

Community Repos:

* [jorgebastida/awslogs :fire::fire::fire::fire:](https://github.com/jorgebastida/awslogs) - Simple CLI for querying groups, streams and events. :star:1991
* [newrelic-platform/newrelic_aws_cloudwatch_plugin :fire:](https://github.com/newrelic-platform/newrelic_aws_cloudwatch_plugin) - New Relic plugin. :star:153

### Code Deploy

AWS Repos:

* [aws-codedeploy-agent :fire:](https://github.com/aws/aws-codedeploy-agent) - Sample agent. :star:172
* [aws-codedeploy-plugin :fire:](https://github.com/awslabs/aws-codedeploy-plugin) - Jenkins plugin. :star:123
* [aws-codedeploy-samples :fire::fire:](https://github.com/awslabs/aws-codedeploy-samples) - Samples and template scenarios. :star:441

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Code Pipeline

AWS Repos:

* [aws-codepipeline-custom-job-worker](https://github.com/awslabs/aws-codepipeline-custom-job-worker) - Develop your own job worker when creating a custom action. :star:17
* [aws-codepipeline-jenkins-aws-codedeploy_linux](https://github.com/awslabs/aws-codepipeline-jenkins-aws-codedeploy_linux) - Four-stage pipeline for Linux. :star:16
* [aws-codepipeline-plugin-for-jenkins](https://github.com/awslabs/aws-codepipeline-plugin-for-jenkins) - Jenkins plugin. :star:57
* [aws-codepipeline-s3-aws-codedeploy_linux](https://github.com/awslabs/aws-codepipeline-s3-aws-codedeploy_linux) - Simple pipeline for Linux. :star:24
* [AWSCodePipeline-Jenkins-AWSCodeDeploy_Windows](https://github.com/awslabs/AWSCodePipeline-Jenkins-AWSCodeDeploy_Windows) - Four-stage pipeline for Windows. :star:4
* [AWSCodePipeline-S3-AWSCodeDeploy_Windows](https://github.com/awslabs/AWSCodePipeline-S3-AWSCodeDeploy_Windows) - Simple pipeline for Windows. :star:5

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Cognito

AWS Repos:

* [amazon-cognito-android](https://github.com/aws/amazon-cognito-android) - Sync SDK for Android. :star:31
* [amazon-cognito-developer-authentication-sample](https://github.com/awslabs/amazon-cognito-developer-authentication-sample) - Authentication sample. :star:80
* [amazon-cognito-dotnet](https://github.com/aws/amazon-cognito-dotnet) - Sync SDK for .NET. :star:4
* [amazon-cognito-ios](https://github.com/aws/amazon-cognito-ios) - Sync SDK for iOS. :star:32
* [amazon-cognito-js :fire:](https://github.com/aws/amazon-cognito-js) - Sync SDK for JavaScript. :star:178
* [amazon-cognito-streams-sample](https://github.com/awslabs/amazon-cognito-streams-sample) - Consuming Streams sample. :star:6
* [cognito-sample-nodejs](https://github.com/awslabs/cognito-sample-nodejs) - Sample App for Node.js. :star:84

Community Repos:

* [capeless/warrant :fire:](https://github.com/capless/warrant) - Python library for using Cognito. :star:175

### Data Pipeline

AWS Repos:

* [data-pipeline-samples :fire::fire:](https://github.com/awslabs/data-pipeline-samples) - Sample pipelines. :star:303

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Device Farm

AWS Repos:

* [aws-device-farm-appium-tests-for-sample-app](https://github.com/awslabs/aws-device-farm-appium-tests-for-sample-app) - Appium TestNG Android tests. :star:54
* [aws-device-farm-calabash-tests-for-sample-app](https://github.com/awslabs/aws-device-farm-calabash-tests-for-sample-app) - Calabash Android tests. :star:9
* [aws-device-farm-gradle-plugin](https://github.com/awslabs/aws-device-farm-gradle-plugin) - Gradle plugin. :star:39
* [aws-device-farm-jenkins-plugin](https://github.com/awslabs/aws-device-farm-jenkins-plugin) - Jenkins plugin. :star:65
* [aws-device-farm-sample-app-for-android](https://github.com/awslabs/aws-device-farm-sample-app-for-android) - Sample Android app. :star:95

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### DynamoDB

AWS Repos:

* [aws-dotnet-session-provider](https://github.com/aws/aws-dotnet-session-provider) - A session state provider for ASP.NET apps. :star:17
* [aws-dotnet-trace-listener](https://github.com/aws/aws-dotnet-trace-listener) - A trace listener for System.Diagnostics that can be used to log events. :star:8
* [aws-dynamodb-encryption-java](https://github.com/awslabs/aws-dynamodb-encryption-java) - Encryption Client for Java. :star:93
* [aws-dynamodb-examples :fire:](https://github.com/awslabs/aws-dynamodb-examples) - Samples using the Java SDK. :star:124
* [aws-dynamodb-mars-json-demo](https://github.com/awslabs/aws-dynamodb-mars-json-demo) - Stores and indexes NASA JPL Mars images. :star:44
* [aws-dynamodb-session-tomcat](https://github.com/aws/aws-dynamodb-session-tomcat) - Session store for Apache Tomcat. :star:92
* [aws-sessionstore-dynamodb-ruby](https://github.com/aws/aws-sessionstore-dynamodb-ruby) - Handles sessions for Ruby web apps. :star:43
* [dynamodb-cross-region-library :fire::fire:](https://github.com/awslabs/dynamodb-cross-region-library) - Cross-region replication. :star:228
* [dynamodb-geo :fire::fire:](https://github.com/awslabs/dynamodb-geo) - Library to create and query geospatial data. :star:215
* [dynamodb-import-export-tool](https://github.com/awslabs/dynamodb-import-export-tool) - Import and export examples. :star:57
* [dynamodb-online-index-violation-detector](https://github.com/awslabs/dynamodb-online-index-violation-detector) - Finds violations on an online GSI's hash key and range key. :star:5
* [dynamodb-streams-kinesis-adapter](https://github.com/awslabs/dynamodb-streams-kinesis-adapter) - Kinesis interface to consume and process data from a DynamoDB stream. :star:41
* [dynamodb-tictactoe-example-app](https://github.com/awslabs/dynamodb-tictactoe-example-app) - Lightweight python app. :star:33
* [dynamodb-titan-storage-backend :fire::fire:](https://github.com/awslabs/dynamodb-titan-storage-backend) - Storage Backend for Titan. :star:352
* [dynamodb-transactions :fire::fire:](https://github.com/awslabs/dynamodb-transactions) - Performs atomic writes and isolated reads across multiple items and tables. :star:249
* [logstash-input-dynamodb](https://github.com/awslabs/logstash-input-dynamodb) - Logstash input plugin. :star:85

Community Repos:

* [channl/dynamodb-lambda-autoscale :fire::fire:](https://github.com/channl/dynamodb-lambda-autoscale) - Autoscale DynamoDB provisioned capacity using Lambda. :star:311
* [lyft/confidant :fire::fire::fire::fire:](https://github.com/lyft/confidant) - Stores secrets, encrypted at rest. :star:1302
* [sebdah/dynamic-dynamodb :fire::fire::fire:](https://github.com/sebdah/dynamic-dynamodb) - Provides auto-scaling. :star:579

### Elastic Beanstalk

AWS Repos:

* [aws-eb-glassfish-dockerfiles](https://github.com/aws/aws-eb-glassfish-dockerfiles) - GlassFish docker files. :star:23
* [aws-eb-python-dockerfiles](https://github.com/aws/aws-eb-python-dockerfiles) - Python docker files. :star:51
* [eb-demo-php-simple-app :fire:](https://github.com/awslabs/eb-demo-php-simple-app) - Simple PHP app. :star:101
* [eb-docker-multiple-ports](https://github.com/awslabs/eb-docker-multiple-ports) - Simple Node.js and Tomcat apps using Docker images. :star:50
* [eb-docker-nginx-proxy](https://github.com/awslabs/eb-docker-nginx-proxy) - Simple PHP app using the PHP-FPM and Nginx Docker images. :star:89
* [eb-docker-virtual-hosting](https://github.com/awslabs/eb-docker-virtual-hosting) - Simple PHP, Tomcat, and Nginx applications using Docker images. :star:24
* [eb-node-express-sample :fire:](https://github.com/awslabs/eb-node-express-sample) - Sample express app. :star:132
* [eb-node-express-signup](https://github.com/awslabs/eb-node-express-signup) - Express framework and Bootstrap Node.js sample app. :star:70
* [eb-node-express](https://github.com/awslabs/eb-node-express) - Sample app referenced in the Developer Guide. :star:7
* [eb-py-flask-signup-worker](https://github.com/awslabs/eb-py-flask-signup-worker) - Python app that illustrates worker roles. :star:32
* [eb-py-flask-signup :fire::fire:](https://github.com/awslabs/eb-py-flask-signup) - Python signup form app with Flask and Bootstrap. :star:221
* [eb-python-flask](https://github.com/awslabs/eb-python-flask) - Simple Python and Flask app. :star:23
* [eb-wif-sample](https://github.com/awslabs/eb-wif-sample) - Sample login app with Web Identity Federation. :star:16

Community Repos:

* [alienfast/elastic-beanstalk :fire:](https://github.com/alienfast/elastic-beanstalk) - Gem with rake configuration and deployment for rails apps. :star:192
* [ThoughtWorksStudios/eb_deployer :fire::fire:](https://github.com/ThoughtWorksStudios/eb_deployer) - Blue-green deployment automation. :star:368

### Elastic Compute Cloud

AWS Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

Community Repos:

* [alestic/ec2-consistent-snapshot :fire::fire:](https://github.com/alestic/ec2-consistent-snapshot) - Initiate consistent EBS snapshots in EC2. :star:431
* [ConradIrwin/aws-name-server :fire::fire::fire:](https://github.com/ConradIrwin/aws-name-server) - DNS server that lets you look up instances by name. :star:548
* [cristim/autospotting :fire::fire::fire:](https://github.com/cristim/autospotting) - Automatically rolling-replace on-demand EC2 instances in AutoScaling groups with compatible spot instances. :star:896
* [evannuil/aws-snapshot-tool :fire:](https://github.com/evannuil/aws-snapshot-tool) - Automates EBS snapshots and rotation. :star:196
* [kelseyhightower/kubernetes-the-hard-way :fire::fire::fire::fire::fire:](https://github.com/kelseyhightower/kubernetes-the-hard-way) - Bootstrap Kubernetes the hard way on EC2. No scripts. :star:9828
* [mirakui/ec2ssh :fire::fire:](https://github.com/mirakui/ec2ssh) - SSH config manager. :star:205
* [openebs/openebs :fire::fire::fire::fire::fire:](https://github.com/openebs/openebs) - Containerized block storage QoS SLAs, tiering and replica policies across AZs and environments, and predictable and scalable performance. :star:5214
* [skavanagh/EC2Box :fire::fire:](https://github.com/skavanagh/EC2Box) - A web-based SSH console to manage multiple instances simultaneously. :star:380
* [wbailey/claws :fire:](https://github.com/wbailey/claws) - CLI-driven console with capistrano integration. :star:168

### Elastic Container Service

AWS Repos:

* [amazon-ecs-agent :fire::fire::fire::fire:](https://github.com/aws/amazon-ecs-agent) - Agent that runs on and starts containers. :star:1230
* [amazon-ecs-amazon-efs](https://github.com/awslabs/amazon-ecs-amazon-efs) - Persists Data from containers. :star:45
* [amazon-ecs-init :fire:](https://github.com/aws/amazon-ecs-init) - RPM developed to support the Amazon ECS Container Agent. :star:102
* [blox :fire::fire::fire:](https://github.com/blox/blox) - Open source tools for building custom schedulers on ECS. :star:854
* [ecs-blue-green-deployment :fire:](https://github.com/awslabs/ecs-blue-green-deployment) - Blue-green deployment on ECS. :star:176
* [ecs-cloudwatch-logs](https://github.com/awslabs/ecs-cloudwatch-logs) - Assets from the blog using Amazon ECS and Amazon CloudWatch logs. :star:60
* [ecs-demo-php-simple-app](https://github.com/awslabs/ecs-demo-php-simple-app) - Simple PHP app. :star:77
* [ecs-mesos-scheduler-driver :fire:](https://github.com/awslabs/ecs-mesos-scheduler-driver) - Integrates Apache Mesos. :star:168
* [ecs-refarch-continuous-deployment :fire::fire:](https://github.com/awslabs/ecs-refarch-continuous-deployment) - Reference Architecture for continuous deployment to ECS using CodePipeline. :star:435
* [ecs-task-kite](https://github.com/awslabs/ecs-task-kite) - Simple ambassador container for inter-task communication. :star:47
* [lambda-ecs-worker-pattern :fire::fire:](https://github.com/awslabs/lambda-ecs-worker-pattern) - Extends Lambda using SQS and ECS. :star:211
* [py-flask-signup-docker](https://github.com/awslabs/py-flask-signup-docker) - Python sample app. :star:63
* [service-discovery-ecs-consul](https://github.com/awslabs/service-discovery-ecs-consul) - Assets from the blog Service Discovery via Consul with Amazon ECS. :star:96

Community Repos:

* [Lumoslabs/broadside](https://github.com/lumoslabs/broadside) - Command line tool for deploying revisions of containerized applications. :star:31

### Elastic File System

AWS Repos:

* [amazon-ecs-amazon-efs](https://github.com/awslabs/amazon-ecs-amazon-efs) - Persist data from ECS. :star:45

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Elastic MapReduce

AWS Repos:

* [emr-bootstrap-actions :fire::fire::fire:](https://github.com/awslabs/emr-bootstrap-actions) - Sample bootstrap actions. :star:508
* [emr-sample-apps](https://github.com/awslabs/emr-sample-apps) - Sample apps. :star:52

Community Repos:

* [Yelp/mrjob :fire::fire::fire::fire::fire:](https://github.com/Yelp/mrjob) - Run MapReduce jobs on Hadoop or EMR. :star:2238

### Elastic Search

AWS Repos:

* [logstash-output-amazon_es :fire::fire:](https://github.com/awslabs/logstash-output-amazon_es) - Logstash output plugin to sign and export events. :star:246
* [opsworks-elasticsearch-cookbook](https://github.com/awslabs/opsworks-elasticsearch-cookbook) - OpsWorks Elasticsearch sample cookbook. :star:34

Community Repos:

* [elastic/elasticsearch-cloud-aws :fire::fire::fire:](https://github.com/elastic/elasticsearch-cloud-aws) - Plugin for Elasticsearch. :star:583

### Elasticache

AWS Repos:

* [aws-elasticache-cluster-client-libmemcached](https://github.com/awslabs/aws-elasticache-cluster-client-libmemcached) - Libmemcached library support. :star:18
* [aws-elasticache-cluster-client-memcached-for-java](https://github.com/awslabs/aws-elasticache-cluster-client-memcached-for-java) - Client for Java. :star:60
* [aws-elasticache-cluster-client-memcached-for-php](https://github.com/awslabs/aws-elasticache-cluster-client-memcached-for-php) - Enhanced PHP library connecting to ElastiCache. :star:39
* [elasticache-cluster-config-net](https://github.com/awslabs/elasticache-cluster-config-net) - Config object for Enyim's MemcachedClient to enable auto discovery. :star:16

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Glacier

Community Repos:

* [vsespb/mt-aws-glacier :fire::fire:](https://github.com/vsespb/mt-aws-glacier) - Perl Multithreaded Multipart sync to Glacier. :star:457

### Kinesis

AWS Repos:

* [amazon-kinesis-aggregators :fire:](https://github.com/awslabs/amazon-kinesis-aggregators) - Provides a simple way to create real time aggregations. :star:129
* [amazon-kinesis-client-net](https://github.com/awslabs/amazon-kinesis-client-net) - Client Library for .NET. :star:36
* [amazon-kinesis-client-nodejs :fire:](https://github.com/awslabs/amazon-kinesis-client-nodejs) - Client Library for Node.js. :star:153
* [amazon-kinesis-client-python :fire::fire:](https://github.com/awslabs/amazon-kinesis-client-python) - Client Library for Python. :star:210
* [amazon-kinesis-client-ruby :fire:](https://github.com/awslabs/amazon-kinesis-client-ruby) - Client Library for Ruby. :star:109
* [amazon-kinesis-client :fire::fire:](https://github.com/awslabs/amazon-kinesis-client) Client library for Amazon Kinesis.
* [amazon-kinesis-connectors :fire::fire:](https://github.com/awslabs/amazon-kinesis-connectors) - Libary to integrate with other AWS and non-AWS services. :star:281
* [amazon-kinesis-data-visualization-sample :fire:](https://github.com/awslabs/amazon-kinesis-data-visualization-sample) - Sample data visualization app. :star:141
* [amazon-kinesis-learning](https://github.com/awslabs/amazon-kinesis-learning) - Learning Kinesis Development. :star:43
* [amazon-kinesis-producer :fire:](https://github.com/awslabs/amazon-kinesis-producer) - Producer Library. :star:182
* [amazon-kinesis-scaling-utils :fire::fire:](https://github.com/awslabs/amazon-kinesis-scaling-utils) - Provides the ability to scale streams. :star:221
* [aws-fluent-plugin-kinesis :fire:](https://github.com/awslabs/aws-fluent-plugin-kinesis) - Fluent Plugin. :star:187
* [dynamodb-streams-kinesis-adapter](https://github.com/awslabs/dynamodb-streams-kinesis-adapter) - DynamoDB Streams Adapter. :star:41
* [kinesis-log4j-appender](https://github.com/awslabs/kinesis-log4j-appender) - Log4J Appender. :star:52
* [kinesis-poster-worker](https://github.com/awslabs/kinesis-poster-worker) - Simple multi-threaded Python Poster and Worker. :star:56
* [kinesis-storm-spout :fire:](https://github.com/awslabs/kinesis-storm-spout) - Spout for Storm. :star:105
* [mqtt-kinesis-bridge](https://github.com/awslabs/mqtt-kinesis-bridge) - Simple MQTT bridge in Python. :star:32

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Lambda

AWS Repos:

* [amazon-elasticsearch-lambda-samples :fire::fire:](https://github.com/awslabs/amazon-elasticsearch-lambda-samples) - Data ingestion for Elasticsearch from S3 and Kinesis. :star:241
* [awslabs/aws-sam-local :fire::fire::fire::fire::fire:](https://github.com/awslabs/aws-sam-local) - CLI tool for local development and testing of Serverless applications. :star:2530
* [aws-lambda-go :fire::fire::fire::fire:](https://github.com/aws/aws-lambda-go) - Libraries, samples and tools to help Go developers develop Lambda functions. :star:1342
* [aws-lambda-java-libs :fire:](https://github.com/aws/aws-lambda-java-libs) - Official mirror for interface definitions and helper classes. :star:147
* [aws-lambda-redshift-loader :fire::fire:](https://github.com/awslabs/aws-lambda-redshift-loader) - Redshift loader. :star:412
* [chalice :fire::fire::fire::fire::fire:](https://github.com/awslabs/chalice) - Python Serverless Microframework. :star:4350
* [create-thumbnails-lambda](https://github.com/awslabs/create-thumbnails-lambda) - Uses the grunt-aws-lambda plugin to help you develop and test. :star:20
* [lambda-ecs-worker-pattern :fire::fire:](https://github.com/awslabs/lambda-ecs-worker-pattern) - Extends Lambda using SQS and ECS. :star:211
* [lambda-refarch-fileprocessing :fire::fire:](https://github.com/awslabs/lambda-refarch-fileprocessing) - Reference Architecture for Real-time File Processing. :star:219
* [lambda-refarch-iotbackend :fire:](https://github.com/awslabs/lambda-refarch-iotbackend) - Reference Architecture for creating an IoT Backend. :star:187
* [lambda-refarch-mobilebackend :fire::fire:](https://github.com/awslabs/lambda-refarch-mobilebackend) - Reference Architecture for creating a Mobile Backend. :star:407
* [lambda-refarch-webapp :fire::fire::fire:](https://github.com/awslabs/lambda-refarch-webapp) - Reference Architecture for creating a Web Application. :star:577

Community Repos:

* [alestic/lambdash :fire::fire:](https://github.com/alestic/lambdash) - Lambda shell - Run sh commands inside the Lambda environment. :star:337
* [Alephbet/gimel :fire:](https://github.com/Alephbet/gimel) - Run your own A/B testing backend using Lambda. :star:174
* [apex/apex :fire::fire::fire::fire::fire:](https://github.com/apex/apex) - Minimal AWS Lambda function manager with Go support. :star:7039
* [claudiajs/claudia :fire::fire::fire::fire::fire:](https://github.com/claudiajs/claudia) - Deploy Node.js projects to Lambda and API Gateway easily. :star:2768
* [cloudnative/lambda-chat :fire::fire:](https://github.com/cloudnative/lambda-chat) - A chat application without servers. :star:363
* [danilop/LambdAuth :fire::fire::fire::fire:](https://github.com/danilop/LambdAuth) - Sample authentication service. :star:1214
* [eawsy/aws-lambda-go :fire::fire::fire:](https://github.com/eawsy/aws-lambda-go) - A fast and clean way to execute Go on Lambda. :star:714
* [garnaat/kappa :fire::fire::fire:](https://github.com/garnaat/kappa) - Kappa is a CLI tool that makes it easier to deploy, update, and test functions for AWS Lambda. :star:890
* [goadapp/goad :fire::fire:fire::fire::fire:](https://github.com/goadapp/goad) - Lambda powered, highly distributed, load testing tool. :star:1543
* [graphcool/chromeless :fire::fire::fire::fire::fire:](https://github.com/graphcool/chromeless) - Automate Chrome through Lambda. :star:12678
* [jimpick/lambda-comments :fire::fire::fire:](https://github.com/jimpick/lambda-comments) - Blog commenting system built with Lambda. :star:583
* [jorgebastida/gordon :fire::fire::fire::fire:](https://github.com/jorgebastida/gordon) - λ Gordon is a tool to create, wire and deploy AWS Lambdas using CloudFormation. :star:1994
* [ks888/LambStatus :fire::fire::fire:](https://github.com/ks888/LambStatus) - A status page system inspired by StatusPage.io, built on AWS Lambda. :star:960
* [kubek2k/lambdoku :fire::fire::fire:](https://github.com/kubek2k/lambdoku) - Heroku-like experience when using Lambda. :star:576
* [lambci/lambci :fire::fire::fire::fire::fire:](https://github.com/lambci/lambci) - A continuous integration system built on Lambda. :star:3077
* [littlstar/s3-lambda :fire::fire::fire::fire:](https://github.com/littlstar/s3-lambda) - Lambda functions over S3 objects with concurrency control (each, map, reduce, filter). :star:1050
* [mentum/lambdaws :fire::fire::fire::fire:](https://github.com/mentum/lambdaws) - Deploy, run and get results in a breeze. :star:1269
* [Miserlou/Zappa :fire::fire::fire::fire::fire:](https://github.com/Miserlou/Zappa) - Serverless WSGI Python Web Apps with AWS Lambda + API Gateway. :star:7131
* [nficano/python-lambda :fire::fire::fire:](https://github.com/nficano/python-lambda) - A toolkit for developing and deploying serverless Python code in Lambda. :star:717
* [serverless/serverless :fire::fire::fire::fire::fire:](https://github.com/serverless/serverless) The Serverless Application Framework (formerly JAWS).
* [Tim-B/grunt-aws-lambda :fire::fire:](https://github.com/Tim-B/grunt-aws-lambda) - Grunt plugin. :star:257
* [trek10inc/aws-lambda-debugger :fire::fire:](https://github.com/trek10inc/aws-lambda-debugger) - Remote debugging tool for Lambda functions running on Node 6.10 :star:230

### Machine Learning

AWS Repos:

* [machine-learning-samples :fire::fire::fire:](https://github.com/awslabs/machine-learning-samples) - Sample apps. :star:722

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Mobile Analytics

AWS Repos:

* [aws-sdk-mobile-analytics-js](https://github.com/aws/aws-sdk-mobile-analytics-js) - JavaScript SDK. :star:76

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### OpsWorks

AWS Repos:

* [opsworks-attribute-customization](https://github.com/awslabs/opsworks-attribute-customization) - Attribute customization example. :star:4
* [opsworks-capistrano](https://github.com/awslabs/opsworks-capistrano) - Capistrano with instances. :star:9
* [opsworks-cloudwatch-logs-cookbooks](https://github.com/awslabs/opsworks-cloudwatch-logs-cookbooks) - CloudWatch sample cookbook. :star:7
* [opsworks-cookbooks :fire::fire::fire::fire:](https://github.com/aws/opsworks-cookbooks) - Chef Cookbooks. :star:1022
* [opsworks-demo-php-photo-share-app](https://github.com/awslabs/opsworks-demo-php-photo-share-app) - Simple PHP photo share app. :star:13
* [opsworks-demo-php-simple-app](https://github.com/awslabs/opsworks-demo-php-simple-app) - Simple PHP app. :star:29
* [opsworks-demo-rails-photo-share-app](https://github.com/awslabs/opsworks-demo-rails-photo-share-app) - A sample Rails app. :star:13
* [opsworks-elasticsearch-cookbook](https://github.com/awslabs/opsworks-elasticsearch-cookbook) - Elasticsearch sample cookbook. :star:34
* [opsworks-example-cookbooks](https://github.com/awslabs/opsworks-example-cookbooks) - Cookbooks used with the sample apps. :star:92
* [opsworks-first-cookbook](https://github.com/awslabs/opsworks-first-cookbook) - Cookbook used to demonstrate simple recipes. :star:8
* [opsworks-windows-demo-](https://github.com/awslabs/opsworks-windows-demo-nodejs) - A sample Node.JS app. :star:15
* [opsworks-windows-demo-cookbooks](https://github.com/awslabs/opsworks-windows-demo-cookbooks) - Cookbooks for Windows. :star:5
* [todo-sample-app-cookbooks](https://github.com/awslabs/todo-sample-app-cookbooks) - Custom cookbooks associated with the todo-sample-app. :star:5

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Redshift

AWS Repos:

* [aws-lambda-redshift-loader :fire::fire:](https://github.com/awslabs/aws-lambda-redshift-loader) - Lambda database loader. :star:412
* [amazon-redshift-utils :fire::fire::fire::fire:](https://github.com/awslabs/amazon-redshift-utils) - Applies optimal Column Encoding to existing Tables. :star:1124

Community Repos:

* [Lumoslabs/aleph](https://github.com/lumoslabs/aleph) - A full featured web application for writing and running Redshift :star:60
queries. Supports revision tracking of queries and has basic visualization support.
* [getredash/redash :fire::fire::fire::fire::fire:](https://github.com/getredash/redash/) - A web application that allows to easily query an existing database, share the dataset and visualize it in different ways. Initially was developed to work with Redshift, and has great support for it.
* [everythingMe/redshift_console](https://github.com/EverythingMe/redshift_console) -  A simple tool to monitor and manage a Redshift cluster. The first release has basic tools to monitor running queries, WLM queue and your tables/schemas. :star:93

### Route 53

AWS Repos:

* [route53-infima :fire:](https://github.com/awslabs/route53-infima) - Manages service-level fault isolation. :star:137

Community Repos:

* [barnybug/cli53 :fire::fire::fire::fire:](https://github.com/barnybug/cli53) - cli53 is a command line tool for Amazon Route 53 which provides import and export from BIND format and simple command line management of Route 53 domains. :star:1187
* [winebarrel/roadworker :fire::fire:](https://github.com/winebarrel/roadworker) - Roadworker is a tool to manage Route53. It defines the state of Route53 using DSL, and updates Route53 according to DSL. :star:278

### S3

Community Repos:

* [anomalizer/ngx_aws_auth :fire::fire:](https://github.com/anomalizer/ngx_aws_auth) - Implements proxying of authenticated requests. :star:264
* [bloomreach/s4cmd :fire::fire::fire:](https://github.com/bloomreach/s4cmd) - S3 command line tool, faster than S3cmd for large files. :star:717
* [CulturalMe/meteor-slingshot :fire::fire::fire:](https://github.com/CulturalMe/meteor-slingshot) - Upload files in meteor. :star:594
* [danilop/yas3fs :fire::fire:](https://github.com/danilop/yas3fs) - Yet Another S3-backed File System, inspired by s3fs. :star:485
* [grippy/node-s3](https://github.com/grippy/node-s3) - Node.js app to manage buckets. :star:95
* [jubos/fake-s3 :fire::fire::fire::fire::fire:](https://github.com/jubos/fake-s3) - Lightweight S3 clone that simulates most commands. :star:2352
* [kahing/goofys :fire::fire::fire::fire:](https://github.com/kahing/goofys) -  a Filey System for Amazon S3 written in Go. :star:1413
* [littlstar/s3renity :fire::fire::fire::fire:](https://github.com/littlstar/s3renity) - Batch functions with concurrency control (each, map, reduce, filter, join)
* [marcel/aws-s3 :fire::fire::fire:](https://github.com/marcel/aws-s3) - Ruby implementation of Amazon's S3 REST API. :star:788
* [mardix/flask-cloudy :fire:](https://github.com/mardix/flask-cloudy) - Flask extension. :star:184
* [MathieuLoutre/grunt-aws-s3 :fire::fire:](https://github.com/MathieuLoutre/grunt-aws-s3) - Grunt plugin. :star:300
* [minio/mc :fire::fire::fire:](https://github.com/minio/mc) -  Minio Client for filesystem and cloud storage. :star:751
* [minio/minio :fire::fire::fire::fire::fire:](https://github.com/minio/minio) - Object storage server compatible with S3. :star:11620
* [mumrah/s3-multipart :fire:](https://github.com/mumrah/s3-multipart) - Parallel upload/download to S3 via Python. :star:133
* [ncw/rclone :fire::fire::fire::fire::fire:](https://github.com/ncw/rclone) - Rsync for various cloud storage providers such as S3. :star:9443
* [owocki/s3_disk_util :fire:](https://github.com/owocki/s3_disk_util) - S3 Disk usage (du) utility. :star:156
* [pgherveou/gulp-awspublish :fire::fire:](https://github.com/pgherveou/gulp-awspublish) - Gulp plugin. :star:373
* [rlmcpherson/s3gof3r :fire::fire::fire:](https://github.com/rlmcpherson/s3gof3r) - Fast, concurrent, streaming access, includes a CLI. :star:920
* [s3git/s3git :fire::fire::fire:](https://github.com/s3git/s3git) - CLI tool that allows you to create a distributed, decentralized and versioned repository. :star:949
* [s3fs-fuse/s3fs-fuse :fire::fire::fire::fire::fire:](https://github.com/s3fs-fuse/s3fs-fuse) - Allows Linux and Mac OS X to mount an S3 bucket via FUSE. :star:2622
* [s3tools/s3cmd :fire::fire::fire::fire::fire:](https://github.com/s3tools/s3cmd) - CLI for managing S3 and CloudFront. :star:2679
* [schickling/git-s3 :fire::fire:](https://github.com/schickling/git-s3) - Deploy your git repo to a bucket. :star:221
* [sorentwo/carrierwave-aws :fire::fire:](https://github.com/sorentwo/carrierwave-aws) - Adapter for CarrierWave. :star:309
* [spring-projects/aws-maven :fire:](https://github.com/spring-projects/aws-maven) -  Maven Wagon for S3. :star:196
* [tongwang/s3fs-c :fire:](https://github.com/tongwang/s3fs-c) - Mounts buckets for use on a local file system. :star:128
* [twpayne/s3-parallel-put :fire::fire:](https://github.com/twpayne/s3-parallel-put) - CLI that supports parallel uploads. :star:218
* [waynehoover/s3_direct_upload :fire::fire::fire:](https://github.com/waynehoover/s3_direct_upload) - Direct Upload to Amazon S3 With CORS :star:630
* [weavejester/clj-aws-s3 :fire:](https://github.com/weavejester/clj-aws-s3) - Client library for Clojure. :star:198

### SES

Community Repos:

* [drewblas/aws-ses :fire::fire::fire:](https://github.com/drewblas/aws-ses) - Provides an easy ruby DSL & interface. :star:505
* [microapps/MoonMail :fire::fire::fire::fire:](https://github.com/microapps/MoonMail) - Shoot billions of emails using SES and Lambda. :star:1191

### Simple Workflow

AWS Repos:

* [aws-flow-ruby :fire:](https://github.com/aws/aws-flow-ruby) - Creates background jobs and multistep workflows. :star:141
* [aws-flow-ruby-samples](https://github.com/awslabs/aws-flow-ruby-samples) - AWS Flow Framework for Ruby samples. :star:63
* [aws-flow-ruby-opsworks-helloworld](https://github.com/awslabs/aws-flow-ruby-opsworks-helloworld) - Hello World sample. :star:5

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### SimpleDB

Community Repos:

* [rjrodger/simpledb :fire:](https://github.com/rjrodger/simpledb) - Node.js library. :star:142

### SNS

AWS Repos:

* [aws-php-sns-message-validator](https://github.com/aws/aws-php-sns-message-validator) - Message validation for PHP. :star:72

Community Repos:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### SQS

AWS Repos:

* [amazon-sqs-java-messaging-lib](https://github.com/awslabs/amazon-sqs-java-messaging-lib) - Holds the Java Message Service to communicate with SQS. :star:72

Community Repos:

* [phstc/shoryuken :fire::fire::fire::fire:](https://github.com/phstc/shoryuken) - A super efficient SQS thread based message processor for Ruby. :star:1226

### Data

Community Repos:

* [donnemartin/data-science-ipython-notebooks :fire::fire::fire::fire::fire:](https://github.com/donnemartin/data-science-ipython-notebooks) - Big data/data science notebooks. :star:12729
* [everpeace/vagrant-mesos :fire::fire:](https://github.com/everpeace/vagrant-mesos) - Spin up your Mesos Cluster with Vagrant. :star:453
* [jhorey/ferry :fire::fire:](https://github.com/jhorey/ferry) -  Define, run, and deploy big data apps using Docker. :star:255
* [nathanmarz/storm-deploy :fire::fire::fire:](https://github.com/nathanmarz/storm-deploy) - One click deploy for Storm clusters. :star:521

### DevOps

Community Repos:

* [capitalone/cloud-custodian :fire::fire::fire::fire:](https://github.com/capitalone/cloud-custodian) - Rules engine for management, DSL in yaml for query, filter, and actions on resources. :star:1387
* [chef-cookbooks/aws :fire::fire:](https://github.com/chef-cookbooks/aws) - Development repository for aws Chef cookbook. :star:371
* [colinbjohnson/aws-missing-tools :fire::fire::fire::fire:](https://github.com/colinbjohnson/aws-missing-tools) - Tools for managing resources including EC2, EBS, RDS and Route53. :star:1159
* [k1LoW/awspec :fire::fire::fire:](https://github.com/k1LoW/awspec) - RSpec tests your resources. :star:671
* [mitchellh/vagrant-aws :fire::fire::fire::fire::fire:](https://github.com/mitchellh/vagrant-aws) - Use Vagrant to manage your EC2 and VPC instances. :star:2419
* [NixOS/nixops :fire::fire:](https://github.com/NixOS/nixops) - Use NixOS to provision EC2 instances, S3 buckets, and other resources. :star:410

### Security

AWS Repos:

* [aws-sha256-agentcs](https://github.com/awslabs/aws-sha256-agentcs) - SHA256 Agent Compatibility Ccanner. :star:4
* [aws-tvm-anonymous](https://github.com/awslabs/aws-tvm-anonymous) - Token Vending Machine for Anonymous Registration. :star:29
* [aws-tvm-identity](https://github.com/awslabs/aws-tvm-identity) - Token Vending Machine for Identity Registration. :star:33
* [s2n :fire::fire::fire::fire::fire:](https://github.com/awslabs/s2n) - An implementation of the TLS/SSL protocols. :star:3122

Community Repos:

* [AdRoll/hologram :fire::fire::fire:](https://github.com/AdRoll/hologram) - Easy, painless credentials on developer laptops. :star:604
* [alex/letsencrypt-aws :fire::fire::fire:](https://github.com/alex/letsencrypt-aws) - Automatically provision and update certificates. :star:711
* [cloudsploit/scans :fire::fire:](https://github.com/cloudsploit/scans) - Detects security risks. :star:497
* [iSECPartners/Scout2 :fire::fire::fire::fire:](https://github.com/iSECPartners/Scout2) - Security auditing tool. :star:1113
* [jordanpotti/AWSBucketDump :fire::fire::fire:](https://github.com/jordanpotti/AWSBucketDump) - Security Tool to Look For Interesting Files in S3 Buckets. :star:520
* [Netflix/bless :fire::fire::fire::fire:](https://github.com/Netflix/bless) - SSH Certificate Authority that runs as a Lambda function. :star:1514
* [Netflix/security_monkey :fire::fire::fire::fire::fire:](https://github.com/Netflix/security_monkey) - Monitors policy changes and alerts on insecure configurations. :star:2699
* [RiotGames/cloud-inquisitor :fire::fire:](https://github.com/RiotGames/cloud-inquisitor) - Tool to enforce ownership and data security. :star:270
* [sebsto/AWSVPN :fire:](https://github.com/sebsto/AWSVPN) - Start a private VPN server in the cloud. :star:166
* [trailofbits/algo :fire::fire::fire::fire::fire:](https://github.com/trailofbits/algo) - Set up a personal IPSEC VPN on EC2 and other cloud services. :star:8900
* [ttlequals0/autovpn :fire::fire::fire::fire:](https://github.com/ttlequals0/autovpn) - Create On Demand Disposable OpenVPN Endpoints. :star:1741

### Accompanying Repos

AWS Repos:

*Repos Accompanying Blogs, Training Events, and Conferences.*

* [aws-arch-backoff-simulator](https://github.com/awslabs/aws-arch-backoff-simulator) - Jitter and backoff Simulator for AWS architecture blog. :star:82
* [aws-big-data-blog :fire::fire::fire:](https://github.com/awslabs/aws-big-data-blog) - Samples from the AWS Big Data Blog. :star:593
* [aws-demo-php-simple-app](https://github.com/awslabs/aws-demo-php-simple-app) - PHP apps from the AWS Blogs. :star:9
* [aws-mobile-sample-wif](https://github.com/awslabs/aws-mobile-sample-wif) - Samples from the AWS Mobile SDK blog. :star:2
* [aws-mobile-self-paced-labs-samples](https://github.com/awslabs/aws-mobile-self-paced-labs-samples) - Android Snake Game from a self-paced lab. :star:11
* [aws-quickstart](https://github.com/aws-quickstart/) - Official repository for AWS Quick Start.
* [aws-spot-labs :fire::fire:](https://github.com/awslabs/aws-spot-labs) - Best practices using AWS Spot Instances. :star:263
* [aws-training-demo :fire:](https://github.com/awslabs/aws-training-demo) - Demos from the Technical Trainers community. :star:100
* [java-meme-generator-sample](https://github.com/awslabs/java-meme-generator-sample) - Meme generation app from re:Invent 2012. :star:40
* [railsconf2013-tech-demo :fire:](https://github.com/awslabs/railsconf2013-tech-demo) - Seahorse demo from RailsConf 2013. :star:167
* [reinvent2013-js-blog-demo](https://github.com/awslabs/reinvent2013-js-blog-demo) - Demo blogging app from re:Invent 2013. :star:28
* [reinvent2013-mobile-photo-share](https://github.com/awslabs/reinvent2013-mobile-photo-share) - Mobile photo share app from re:Invent 2014. :star:20
* [reinvent2014-scalable-site-management](https://github.com/awslabs/reinvent2014-scalable-site-management) - Scalable site management sample from re:Invent 2014. :star:57
* [reinvent2015-dev309](https://github.com/awslabs/reinvent2015-dev309) - Large Scale Metrics Analysis from re:Invent 2015. :star:6
* [timely-security-analytics](https://github.com/awslabs/timely-security-analytics) - Security analytics sample from 2015 re:Invent 2015. :star:25
* [todo-app-railsconf](https://github.com/awslabs/todo-app-railsconf) - Simple "Todo" app from RailsConf 2015. :star:14
* [todo-sample-app](https://github.com/awslabs/todo-sample-app) - Simple "Todo" app from RailsConf 2014. :star:22

Community Repos:

* [startup-class/setup :fire::fire:](https://github.com/startup-class/setup) -  EC2 setup files for Startup Engineering MOOC. :star:297

### Miscellaneous Repos

AWS Repos:

* [amediamanager](https://github.com/awslabs/amediamanager) - Media manager. :star:55
* [aws-hal-client-java](https://github.com/awslabs/aws-hal-client-java) - Java client for the Hypertext Application Language. :star:11
* [aws-model-validators](https://github.com/awslabs/aws-model-validators) - Tools for validating the AWS service JSON model files. :star:6
* [aws-sdk-js-sample-video-transcoder](https://github.com/awslabs/aws-sdk-js-sample-video-transcoder) - Sample cross-platform video transcoder app. :star:18
* [simplebeerservice :fire::fire:](https://github.com/awslabs/simplebeerservice) - Cloud-connected kegerator that streams live sensor data to AWS. :star:212

Community Repos:

* [bcoe/thumbd :fire::fire:](https://github.com/bcoe/thumbd) - Node.js/ImageMagick-based image thumbnailing service. :star:451
* [Comcast/cmb :fire::fire:](https://github.com/Comcast/cmb) - Highly available, horizontally scalable queuing and notification service. :star:276
* [convox/rack :fire::fire::fire::fire:](https://github.com/convox/rack) - Open-source PaaS on AWS. :star:1672
* [devops-israel/aws-inventory :fire::fire:](https://github.com/devops-israel/aws-inventory) - Display all your AWS resources on a single web page. :star:204
* [donnemartin/dev-setup :fire::fire::fire::fire:](https://github.com/donnemartin/dev-setup) - Mac setup of various developer tools and AWS services. :star:3643
* [dtan4/terraforming :fire::fire::fire::fire:](https://github.com/dtan4/terraforming) - Export existing resources to Terraform style (tf, tfstate). :star:1854
* [segmentio/stack :fire::fire::fire::fire:](https://github.com/segmentio/stack) - A set of Terraform modules for configuring production infrastructure. :star:1623
* [j2labs/microarmy ](https://github.com/j2labs/microarmy) - Deploy micro instances to launch a coordinated siege.
* [jpillora/grunt-aws :fire:](https://github.com/jpillora/grunt-aws) - Grunt interface into the Node.JS SDK. :star:177
* [jvehent/haproxy-aws :fire::fire:](https://github.com/jvehent/haproxy-aws) - Documentation on building a HTTPS stack with HAProxy. :star:255
* [localstack/localstack ](https://github.com/atlassian/localstack) - A fully functional local AWS cloud stack. Develop and test your cloud apps offline! :star:43
* [meducation/propono :fire::fire:](https://github.com/meducation/propono) - Easy-to-use pub/sub in Ruby. :star:301
* [mozilla/awsbox :fire::fire::fire:](https://github.com/mozilla/awsbox) - A featherweight PaaS on top of EC2 for deploying node apps. :star:792
* [Netflix/aminator :fire::fire::fire:](https://github.com/Netflix/aminator) - A tool for creating EBS AMIs. :star:762
* [Netflix/archaius :fire::fire::fire::fire:](https://github.com/Netflix/archaius) - Library for configuration management API. :star:1675
* [Netflix/asgard :fire::fire::fire::fire::fire:](https://github.com/Netflix/asgard) - Web interface for application deployments and cloud management. :star:2192
* [Netflix/aws-autoscaling :fire::fire:](https://github.com/Netflix/aws-autoscaling) - Tools for using auto scaling and documentation best practices. :star:407
* [Netflix/chaosmonkey :fire::fire::fire::fire::fire:](https://github.com/Netflix/chaosmonkey) - Resiliency tool that helps applications tolerate random instance failures. :star:4303
* [Netflix/eureka :fire::fire::fire::fire::fire:](https://github.com/Netflix/eureka) - Service registry for resilient mid-tier load balancing and failover. :star:5508
* [Netflix/EVCache :fire::fire::fire:](https://github.com/Netflix/EVCache) - A distributed in-memory data store. :star:859
* [Netflix/Fenzo :fire::fire::fire:](https://github.com/Netflix/Fenzo) - Extensible Scheduler for Mesos Frameworks. :star:629
* [Netflix/ice :fire::fire::fire::fire::fire:](https://github.com/Netflix/ice) - Usage and cost monitoring tool. :star:2480
* [Netflix/ribbon :fire::fire::fire::fire::fire:](https://github.com/Netflix/ribbon) - Remote procedure call library with built in software load balancers. :star:2132
* [Netflix/SimianArmy :fire::fire::fire::fire::fire:](https://github.com/Netflix/SimianArmy) - Tools to keep your cloud operating in top form. :star:6532
* [Netflix/zuul :fire::fire::fire::fire::fire:](https://github.com/Netflix/zuul) - Edge service that provides dynamic routing, monitoring, resiliency, security, and more. :star:5239
* [niftylettuce/gulp-aws-splash :fire::fire:](https://github.com/niftylettuce/gulp-aws-splash) - Open-source LaunchRock alternative. Build beautiful splash pages. :star:443
* [puppetlabs/puppetlabs-aws :fire:](https://github.com/puppetlabs/puppetlabs-aws) - Puppet module for managing resources to build out infrastructure. :star:177
* [mhart/react-server-routing-example :fire::fire:](https://github.com/mhart/react-server-routing-example) - Sample universal client/server routing and data in React. :star:284
* [snowplow/snowplow :fire::fire::fire::fire::fire:](https://github.com/snowplow/snowplow) - Enterprise-strength web, mobile and event analytics, powered by Hadoop, Kafka, Kinesis, Redshift and Elasticsearch. :star:4079
* [Spinnaker/spinnaker :fire::fire::fire::fire::fire:](https://github.com/Spinnaker/spinnaker) - Successor to asgard supporting pipelines and more. :star:4756
* [spulec/moto :fire::fire::fire::fire:](https://github.com/spulec/moto) - Allows your python tests to easily mock out the boto library. :star:1729

## Guides, Books, Documentation, and Training

*How-to's, training, whitepapers, docs, and case studies.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/LxYDN5K.png">
</p>
<br/>

### Getting Started Guides

AWS Guides:

* [Getting Started with AWS](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-intro.html)
* [Getting Started Tutorials](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html)
    * [Run a Virtual Server](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2614)
    * [Store Files](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2683)
    * [Share Digital Media](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2755)
    * [Deploy a Website](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2767)
    * [Host a Website (Linux)](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2836)
    * [Host a Website (Windows)](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2908)
    * [Run a Database](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2980)
    * [Analyze Your Data](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e3065)

Community Guides:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### General Guides

AWS Guides:

* [Analyzing Big Data](http://docs.aws.amazon.com/gettingstarted/latest/emr/getting-started-emr-overview.html)
    * [Sentiment Analysis](http://docs.aws.amazon.com/gettingstarted/latest/emr/getting-started-emr-sentiment-tutorial.html)
    * [Web Server Log Analysis](http://docs.aws.amazon.com/gettingstarted/latest/emr/getting-started-emr-tutorial.html)
* [Working with the AWS Management Console](http://docs.aws.amazon.com/awsconsolehelpdocs/latest/gsg/getting-started.html)
* [Deploying a Web App Using Elastic Beanstalk](http://docs.aws.amazon.com/gettingstarted/latest/deploy/overview.html)
* [Hosting a Web App](http://docs.aws.amazon.com/gettingstarted/latest/wah-linux/web-app-hosting-intro.html)
* [Hosting a .NET Web App](http://docs.aws.amazon.com/gettingstarted/latest/wah/web-app-hosting-intro.html)
* [Hosting a Static Website](http://docs.aws.amazon.com/gettingstarted/latest/swh/website-hosting-intro.html)
* [Quick Start Deployment Guides](https://aws.amazon.com/documentation/quickstart/)

Community Guides:

* [Open Guide to AWS :fire::fire::fire::fire::fire:](https://github.com/open-guides/og-aws) :star:19841

### Books

* Amazon Web Services in Action [Manning](https://www.manning.com/books/amazon-web-services-in-action) or [Amazon.com](http://amzn.com/1617292885)
* AWS Lambda in Action [Manning](https://www.manning.com/books/aws-lambda-in-action) or [Amazon.com](http://amzn.com/1617293717) - [Code Repo :fire:](https://github.com/danilop/AWS_Lambda_in_Action)

### Whitepapers

* [AWS Well-Architected Framework](https://d0.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf)
* [Whitepapers](https://aws.amazon.com/whitepapers/)

### Documentation

* [Documentation](https://aws.amazon.com/documentation/)
* [AWS Billing and Cost Management](https://aws.amazon.com/documentation/account-billing/)
* [AWS Marketplace](https://aws.amazon.com/documentation/marketplace/)
* [AWS Support](https://aws.amazon.com/documentation/aws-support/)
* [AWS General Reference](http://docs.aws.amazon.com/general/latest/gr/)
* [AWS Glossary](http://docs.aws.amazon.com/general/latest/gr/glos-chap.html)

### Training

* [Training and Certification](https://aws.amazon.com/training/)
* [Webinars](https://aws.amazon.com/about-aws/events/)

### Case Studies: Powered by AWS

* [Adobe](https://aws.amazon.com/solutions/case-studies/adobe/?pg=main-customer-success-page)
* [AdRoll](https://aws.amazon.com/solutions/case-studies/adroll/)
* [Airbnb](https://aws.amazon.com/solutions/case-studies/airbnb/?pg=main-customer-success-page)
* [Autodesk](https://aws.amazon.com/solutions/case-studies/autodesk/)
* [AWS](http://aws.amazon.com/)
* [Citrix](https://aws.amazon.com/solutions/case-studies/citrix/)
* [Comcast](https://aws.amazon.com/solutions/case-studies/comcast/?pg=main-customer-success-page)
* [Coursera](https://aws.amazon.com/solutions/case-studies/coursera/)
* [Docker](https://aws.amazon.com/solutions/case-studies/docker/)
* [Dow Jones](https://aws.amazon.com/solutions/case-studies/dow-jones/?pg=main-customer-success-page)
* [Dropbox](https://www.dropbox.com/)
* [Dropcam](https://aws.amazon.com/solutions/case-studies/dropcam/)
* [Expedia](https://aws.amazon.com/solutions/case-studies/expedia/?pg=main-customer-success-page)
* [Foursquare](https://aws.amazon.com/solutions/case-studies/foursquare/?pg=main-customer-success-page)
* [IMDb](https://aws.amazon.com/solutions/case-studies/imdb/)
* [Instrumental](https://instrumentalapp.com/blog/aws-kinesis/) - Deep-dive into Kinesis as a queue system
* [Intuit](https://aws.amazon.com/solutions/case-studies/soasta-intuit/)
* [Johnson & Johnson](https://aws.amazon.com/solutions/case-studies/johnson-and-johnson/)
* [Lionsgate](https://aws.amazon.com/solutions/case-studies/lionsgate/?pg=main-customer-success-page)
* [mlbam](https://aws.amazon.com/solutions/case-studies/major-league-baseball-mlbam/?pg=main-customer-success-page)
* [NASA](https://aws.amazon.com/solutions/case-studies/nasa-jpl-curiosity/?pg=main-customer-success-page)
* [Netflix](https://aws.amazon.com/solutions/case-studies/netflix/?pg=main-customer-success-page)
* [Nike](https://aws.amazon.com/solutions/case-studies/nike/)
* [Nokia](https://aws.amazon.com/solutions/case-studies/nokia/?pg=main-customer-success-page)
* [PBS](https://aws.amazon.com/solutions/case-studies/pbs/)
* [Pfizer](https://aws.amazon.com/solutions/case-studies/pfizer/?pg=main-customer-success-pagel)
* [Philips](https://aws.amazon.com/solutions/case-studies/philips/)
* [Reddit](https://www.reddit.com/)
* [Samsung](https://aws.amazon.com/solutions/case-studies/samsung/?pg=main-customer-success-page)
* [Siemens](https://aws.amazon.com/solutions/case-studies/siemens/)
* [Slack](https://aws.amazon.com/solutions/case-studies/slack/?pg=main-customer-success-page)
* [Spotify](https://www.spotify.com)
* [Swiftkey](https://aws.amazon.com/solutions/case-studies/swiftkey/)
* [The Weather Company](https://aws.amazon.com/solutions/case-studies/the-weather-company/)
* [Ticketmaster](https://aws.amazon.com/solutions/case-studies/ticketmaster/)
* [Time Inc](https://aws.amazon.com/solutions/case-studies/time-inc/?pg=main-customer-success-page)
* [Twilio](https://www.twilio.com/)
* [U.S. Department of State](https://aws.amazon.com/solutions/case-studies/exchangesconnect/)
* [Ubisoft](https://aws.amazon.com/solutions/case-studies/ubisoft/)
* [Yelp](https://aws.amazon.com/solutions/case-studies/yelp-docker/?pg=main-customer-success-page)
* [Zillow](https://aws.amazon.com/solutions/case-studies/zillow/)

## Social

*Blogs, discussion groups, conferences, and social media.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/kRRBa1e.png">
</p>
<br/>

### Blogs

AWS Blogs:

* [Official Blog](https://aws.amazon.com/blogs/aws/)
    * [Brasil](http://aws.typepad.com/brasil/)
    * [China](http://blog.csdn.net/awschina)
    * [Germany](http://aws.typepad.com/awsaktuell/)
    * [Japan](http://aws.typepad.com/aws_japan/)
    * [Korea](http://aws.amazon.com/ko/blogs/korea/)
* [Application Management](http://blogs.aws.amazon.com/application-management)
* [Architecture](http://www.awsarchitectureblog.com/)
* [Big Data](https://blogs.aws.amazon.com/bigdata/)
* [Compute](https://aws.amazon.com/blogs/compute/)
* [Mobile](https://mobile.awsblog.com/)
* [SES](http://sesblog.amazon.com/)
* [Java](http://java.awsblog.com/)
* [PHP](http://blogs.aws.amazon.com/php/)
* [Ruby](http://ruby.awsblog.com/)
* [Security](http://blogs.aws.amazon.com/security/)
* [Startup](https://medium.com/aws-activate-startup-blog)
* [.NET](http://blogs.aws.amazon.com/net/)
* [Partner Network](https://aws.amazon.com/blogs/apn/)
* [SAP](https://aws.amazon.com/blogs/awsforsap/)
* [Startup collection](https://medium.com/aws-activate-startup-blog)

Community Blogs:

* [All Things Distributed](http://www.allthingsdistributed.com/) - Werner Vogels, AWS CTO.
* [Things I Like...](http://jeff-barr.com/) - Jeff Barr, AWS Chief Evangelist.
* [Netflix Tech Blog](http://techblog.netflix.com/)
* [A Curated List of Engineering Blogs](https://github.com/kilimchoi/engineering-blogs) :star:13042
* [AWS Geek](https://www.awsgeek.com/)
* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Twitter Influencers

AWS Tweeps:

* [@awscloud](https://twitter.com/awscloud) - Official Twitter feed.
* [@AWS_Partners](https://twitter.com/AWS_Partners)
* [@AWSIdentity](https://twitter.com/AWSIdentity)
* [@AWSMarketplace](https://twitter.com/AWSMarketplace)
* [@AWSreInvent](https://twitter.com/AWSreInvent) - Official Twitter account for re:Invent.
* [@AWSStartups](https://twitter.com/AWSStartups)
* [@ajassy](https://twitter.com/ajassy) - Andy Jassy: Senior Vice-President.
* [@Ianmmmm](https://twitter.com/Ianmmmm) - Ian Massingham - Technical Evangelist.
* [@jeffbarr](https://twitter.com/jeffbarr) - Jeff Barr: Chief Evangelist.
* [@mndoci](https://twitter.com/mndoci) - Deepak Singh: GM EC2.
* [@mza](https://twitter.com/mza) - Matt Wood: Product Strategy.
* [@Werner](https://twitter.com/Werner) - Werner Vogels: CTO.
* [Community heroes, Evangelists, etc](https://twitter.com/awscloud/lists)

Community Tweeps:

* [@kennwhite](https://twitter.com/kennwhite)
* [@esh](https://twitter.com/esh)
* [@garnaat](https://twitter.com/garnaat)
* [@quinnypig](https://twitter.com/quinnypig)
* [@awsgeek](https://twitter.com/awsgeek)

### Facebook Pages

AWS Pages:

* [amazonwebservices](https://www.facebook.com/amazonwebservices) - Official Facebook page.
* [awsreinvent](https://www.facebook.com/awsreinvent) - Official Facebook page for re:Invent.

Community Pages:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### YouTube Channels

AWS Channels:

* [AmazonWebServices](https://www.youtube.com/user/AmazonWebServices)
* [AWSDeutsch](https://www.youtube.com/user/AWSAktuell)
* [AWSJapan](https://www.youtube.com/user/AmazonWebServicesJP)
* [AWSKorea](https://www.youtube.com/user/AWSKorea)
* [AWSLatinAmerica](https://www.youtube.com/channel/UCvaUAVzIIGsRNlUDWkQFCeA)
* [AWSTutorialSeries](https://www.youtube.com/user/awstutorialseries)
* [AWSWebinars](https://www.youtube.com/user/AWSwebinars)

Community Channels:

* [Backspace Academy](https://www.youtube.com/channel/UCav3fsasRc5VOqvZiT5avgw)
* [Cloud Academy](https://www.youtube.com/channel/UCeRY0LppLWdxWAymRANTb0g/videos)
* [Linux Academy](https://www.youtube.com/user/pineheadtv/playlists)

### LinkedIn Groups

AWS Page:

* [Amazon Web Services](https://www.linkedin.com/company/amazon-web-services)

Community Groups:

* [Amazon AWS Architects](https://www.linkedin.com/grp/home?gid=4387417)
* [Amazon AWS Architects, Engineers, Developers, Consultants, Entrepreneurs Experts](https://www.linkedin.com/grps?gid=3748455)
* [Amazon Web Services (AWS) for Business](https://www.linkedin.com/grps?gid=5122002)
* [Amazon Web Services Architects](https://www.linkedin.com/grps?gid=4233997)
* [Amazon Web Services Community Network](https://www.linkedin.com/grp/home?gid=49531)
* [Amazon Web Services Enthusiasts](https://www.linkedin.com/grps?gid=2485626)
* [Amazon Web Services Users](https://www.linkedin.com/grps?gid=86137)

### Subreddits

* [/r/aws/](https://www.reddit.com/r/aws/)
* [/r/AWS_cloud/](https://www.reddit.com/r/AWS_cloud/)

### Conferences

AWS Conferences:

* [re:Invent](https://reinvent.awsevents.com/) - Annual user conference. The event features keynote announcements, training and certification opportunities, over 250 technical sessions, a partner expo, after hours activities, and more.
* [Summits](https://aws.amazon.com/summits/) - Global one-day events that are designed to educate new customers about the AWS platform and offer existing customers deep technical content to be more successful with AWS.
* [AWSome Day](https://aws.amazon.com/events/awsome-day/awsome-day-online/) - Global one-day events are delivered by AWS Education's technical instructors and are ideal for IT pros, developers and technical managers who would like to learn about how to get started in the AWS Cloud.

Community Conferences:

* [Contribute](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

## Latest KPIs and Stats

*Latest key performance indicators and other interesting stats.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/KP2TmJv.png">
</p>
<br/>

* Over 1 million customers active in past 30 days.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
* $7B+ annual revenue run-rate business.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
    * 81% year over year revenue growth.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
* EC2 usage up 95% year over year.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
* S3 data transfer up 120% year over year.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
    * S3 holds trillions of objects and regularly peaks at 1.5 million requests per second.<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>
* Database services usage up 127% year over year.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
    * $1B annual revenue run-rate business.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
* 2 million new EBS volumes created per day.<sup>[4](https://www.youtube.com/watch?v=OuyUbvtgfDk)</sup>
* Customers have launched more than 15 million Hadoop clusters.<sup>[3](http://www.forbes.com/sites/benkepes/2014/11/25/scale-beyond-comprehension-some-aws-numbers/)</sup>
* 102Tbps network capacity into a data center.<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>
* 500+ major new features and services launched since 2014.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
* All 14 other cloud providers combined have 1/5th the aggregate capacity of AWS.<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>
* Every day, AWS adds enough new server capacity to support all of Amazon's global infrastructure when it was a $7B annual revenue enterprise (in 2004).<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>

## Appendix of Core Services

*Appendix of official services, grouped by service category.*

### Services in Plain English

* [Amazon Web Services in Plain English](https://www.expeditedssl.com/aws-in-plain-english) - Entertaining and educational, a community contribution.

### Compute Services

* [Auto Scaling](https://aws.amazon.com/autoscaling/) - Launches or terminates EC2 instances based on policies, schedules, and health checks.
* [Batch](https://aws.amazon.com/batch/) - Run batch jobs at scale.
* [Blox](https://blox.github.io/) - Open source projects for building custom schedulers on ECS.
* [EC2 Container Service (ECS)](https://aws.amazon.com/ecs/) - Supports Docker containers on EC2 instances.
* [EC2 Systems Manager](https://aws.amazon.com/ec2/systems-manager/) - Easily configure and manage EC2 and on-premises systems.
* [Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) - Provides quick deployment and management of applications in the cloud.
* [Elastic Compute Cloud (EC2)](http://aws.amazon.com/ec2/) - Provides scalable virtual private servers using Xen.
* [Elastic GPUs](https://aws.amazon.com/ec2/Elastic-GPUs/) - Attach low-cost GPUs to EC2 instances for graphics acceleration.
* [Elastic Load Balancing (ELB)](https://aws.amazon.com/elasticloadbalancing/) - Automatically distributes incoming traffic across multiple EC2 instances.
* [Lambda](https://aws.amazon.com/lambda/) - Runs code in response to events and automatically manages EC2 instances.
* [Lightsail](https://amazonlightsail.com/) - Launch and manage simple virtual private servers.
* [Virtual Private Cloud (VPC)](https://aws.amazon.com/vpc/) - Creates a logically isolated set of EC2 instances which can be connected to an existing network using a VPN connection.

### Networking Services

* [Direct Connect](https://aws.amazon.com/directconnect/) - Provides dedicated connections to AWS for faster and cheaper data throughput.
* [Elastic Load Balancing (ELB)](https://aws.amazon.com/elasticloadbalancing/) - Automatically distributes incoming traffic across multiple EC2 instances.
* [Route 53](https://aws.amazon.com/route53/) - Provides a highly available and scalable Domain Name System (DNS) web service.
* [Virtual Private Cloud (VPC)](https://aws.amazon.com/vpc/) - Creates a logically isolated set of EC2 instances which can be connected to an existing network using a VPN connection.

### Enterprise Applications

* [WorkDocs](https://aws.amazon.com/workdocs/) - Provides a fully managed, secure enterprise storage and sharing service.
* [WorkMail](https://aws.amazon.com/workmail/) - Provides managed email and calendaring service.
* [WorkSpaces](https://aws.amazon.com/workspaces/) - Provides a cloud-based desktop experience to end-users.
* [Workspaces Application Manager (WAM)](http://aws.amazon.com/workspaces/applicationmanager/) - Simplifies deployment and management of WorkSpaces.

### Analytics Services

* [Athena](https://aws.amazon.com/athena/) - Query data on S3 instantly.
* [Data Pipeline](https://aws.amazon.com/datapipeline/) - Provides workload management by processing and moving data between services.
* [Elastic MapReduce (EMR)](http://aws.amazon.com/elasticmapreduce/) - Hosts a Hadoop and Spark framework running on EC2 and S3.
* [Elasticsearch Service (ES)](https://aws.amazon.com/elasticsearch-service/) - Managed Elasticsearch, a popular open-source search and analytics engine.
* [Glue](https://aws.amazon.com/glue/) - Prepare and load data to data stores.
* [Kinesis](https://aws.amazon.com/kinesis/) - Provides real-time data processing over large, distributed data streams.
* [Kinesis Analytics](https://aws.amazon.com/kinesis/analytics/) - Write standard SQL queries on streaming data without having to learn any new programming skills.
* [Kinesis Firehose](https://aws.amazon.com/kinesis/firehose/) - Captures and automatically loads streaming data into S3 and Redshift.
* [Quicksight](https://aws.amazon.com/quicksight/) - Provides cloud-powered business intelligence for 1/10th the cost of traditional BI solutions.
* [Redshift](https://aws.amazon.com/redshift/) - Provides petabyte-scale data warehousing with columnar storage and multi-node compute.

### Artificial Intelligence

* [Lex](https://aws.amazon.com/lex/) - Build conversational interfaces through voice or text.
* [Machine Learning](https://aws.amazon.com/machine-learning/) - Provides managed machine learning technology.
* [Polly](https://aws.amazon.com/polly/) - Turn text into lifelike speech.
* [Rekognition](https://aws.amazon.com/rekognition/) - Deep learning-based image analysis.

### Management Tools

* [CloudFormation](https://aws.amazon.com/cloudformation/) - Provides a file-based interface for provisioning other resources.
* [CloudTrail](https://aws.amazon.com/cloudtrail/) - Provides logs of all activity.
* [CloudWatch](https://aws.amazon.com/cloudwatch/) - Provides monitoring for AWS cloud resources and applications, starting with EC2.
* [Command Line Interface (CLI)](https://aws.amazon.com/cli/) - Provides a CLI to manage all services.
* [Config](https://aws.amazon.com/config/) - Provides a detailed view of all resources.
* [Management Console (AWS Console)](https://aws.amazon.com/console/) - A web-based interface to manage all services.
* [OpsWorks](https://aws.amazon.com/opsworks/) - Provides configuration of EC2 services using Chef.
* [Personal Health Dashboard](https://aws.amazon.com/premiumsupport/phd/) - Your personalized view of service health.
* [Service Catalog](https://aws.amazon.com/servicecatalog/) - Service Catalog allows IT administrators to create, manage, and distribute portfolios of approved products to end users, who can then access the products they need in a personalized portal.

### Security and Identity Services

* [Certificate Manager](https://aws.amazon.com/certificate-manager/) - Lets you easily provision, manage, and deploy SSL/TLS certificates for use with AWS services.
* [CloudHSM](https://aws.amazon.com/cloudhsm/) - Helps meet corporate, contractual and regulatory compliance requirements for data security by using dedicated Hardware Security Module (HSM) appliances within the AWS cloud.
* [Directory Service](https://aws.amazon.com/directoryservice/) - A managed service that allows you to connect your resources with an existing on-premises Microsoft Active Directory or to set up a new, stand-alone directory in the AWS Cloud.
* [Identity and Access Management (IAM)](https://aws.amazon.com/iam/) - An implicit service, the authentication infrastructure used to authenticate access to the various services.
* [Inspector](https://aws.amazon.com/inspector/) - An automated security assessment service that helps improve the security and compliance of applications deployed on AWS.
* [Key Management Service (KMS)](https://aws.amazon.com/kms/) - A managed service that makes it easy for you to create and control the encryption keys used to encrypt your data.
* [Shield](https://aws.amazon.com/shield/) - Managed DDoS Protection.
* [WAF](https://aws.amazon.com/waf/) - A web application firewall service that monitors and manages CloudFront distributions.

### Internet of Things Service

* [IoT](https://aws.amazon.com/iot/) - Enables secure, bi-directional communication between internet-connected things (such as sensors, actuators, embedded devices, or smart appliances) and the AWS cloud over MQTT and HTTP.

### Mobile Services

* [API Gateway](https://aws.amazon.com/api-gateway/) - Service for publishing, maintaining and securing web service APIs.
* [Cognito](https://aws.amazon.com/cognito/) - Provides user identity and data synchronization.
* [Device Farm](https://aws.amazon.com/device-farm/) - App testing service for iOS, Android and Fire OS apps on physical devices.
* [Mobile Analytics](https://aws.amazon.com/mobileanalytics/) - Service for collecting, visualizing, and understanding app usage data.
* [Mobile Hub](https://aws.amazon.com/mobile/) - Provides an integrated console that helps you build, test, and monitor your mobile apps.
* [Pinpoint](https://aws.amazon.com/pinpoint/) - Targeted push notifications for mobile apps.
* [Simple Notification Service (SNS)](https://aws.amazon.com/sns/) - Provides a hosted multi-protocol "push" messaging for applications.

### Storage and Content Delivery Services

* [CloudFront](https://aws.amazon.com/cloudfront/) - A content delivery network (CDN) for distributing objects to locations near the requester.
* [Elastic Block Store (EBS)](https://aws.amazon.com/ebs/) - Provides persistent block-level storage volumes for EC2.
* [Elastic File System (EFS)](https://aws.amazon.com/efs/) - A file storage service for EC2 instances.
* [Glacier](https://aws.amazon.com/glacier/) - Provides a low-cost, long-term storage option, intended for archiving data.
* [Import/Export](https://aws.amazon.com/importexport/) - Accelerates moving large amounts of data into and out of AWS using portable storage devices for transport.
* [Simple Storage Service (S3)](https://aws.amazon.com/s3/) - Provides Web Service based storage.
* [Storage Gateway](https://aws.amazon.com/storagegateway/) - An iSCSI block storage virtual appliance with cloud-based backup.

### Databases

* [Aurora](https://aws.amazon.com/rds/aurora/) - MySQL and PostgreSQL compatible relational database with improved performance.
* [DynamoDB](https://aws.amazon.com/dynamodb/) - Provides a scalable, low-latency NoSQL online Database Service backed by SSDs.
* [ElastiCache](https://aws.amazon.com/elasticache/) - Provides in-memory caching for web apps (Memcached, Redis).
* [Redshift](https://aws.amazon.com/redshift/) - Provides petabyte-scale data warehousing with columnar storage and multi-node compute.
* [Relational Database Service (RDS)](https://aws.amazon.com/rds/) - Provides a scalable database server with MySQL, Oracle, SQL Server, PostgreSQL, and MariaDB support.
* [Schema Conversion Tool](https://aws.amazon.com/documentation/SchemaConversionTool/) - App that helps you convert your database schema from an Oracle or Microsoft SQL Server database, to an RDS MySQL DB instance or an Aurora DB cluster.
* [SimpleDB](https://aws.amazon.com/simpledb/) - Allows developers to run queries on structured data.

### Application Services

* [API Gateway](https://aws.amazon.com/api-gateway/) - Service for publishing, maintaining and securing web service APIs.
* [AppStream](https://aws.amazon.com/appstream/) - Flexible, low-latency streaming service for apps and games.
* [CloudSearch](https://aws.amazon.com/cloudsearch/) - Provides basic full-text search and indexing of textual content.
* [DevPay](https://aws.amazon.com/devpay/) - Provides billing and account management.
* [Elastic Transcoder (ETS)](https://aws.amazon.com/elastictranscoder/) - Provides video transcoding of S3 hosted videos.
* [Flexible Payments Service (FPS)](https://payments.amazon.com/developer) - Provides an interface for micropayments.
* [Simple Email Service (SES)](https://aws.amazon.com/ses/) - Provides bulk and transactional email sending.
* [Simple Notification Service (SNS)](https://aws.amazon.com/sns/) - Provides a hosted multi-protocol "push" messaging for applications.
* [Simple Queue Service (SQS)](https://aws.amazon.com/sqs/) - Provides a hosted message queue for web applications.
* [Simple Workflow (SWF)](https://aws.amazon.com/swf/) - A workflow service for building scalable, resilient applications.
* [Step Functions](https://aws.amazon.com/step-functions/) - Coordinate components of distributed applications.

### Developer Tools

* [CodeBuild](https://aws.amazon.com/codebuild/) - Build and test code.
* [CodeCommit](https://aws.amazon.com/documentation/codecommit/) - Hosted Git version control service.
* [CodeDeploy](https://aws.amazon.com/codedeploy/) - Provides automated code deployment to EC2 instances.
* [CodePipeline](https://aws.amazon.com/documentation/codepipeline/) - Continuous delivery service.
* [Command Line Interface (CLI)](https://aws.amazon.com/cli/) - Provides a CLI to manage all services.
* [X-Ray](https://aws.amazon.com/xray/) - Analyze and debug your applications.

### Miscellaneous Services

* [Fulfillment Web Service](https://aws.amazon.com/about-aws/whats-new/2008/03/19/announcing-amazon-fulfillment-web-service/) - Provides a programmatic web service for sellers to ship items to and from Amazon using Fulfillment by Amazon.
* [Mechanical Turk](https://www.mturk.com/mturk/welcome) - Manages small units of work distributed among many persons.
* [Partner Network (APN)](https://aws.amazon.com/partners/) - Provides partners with the technical information and sales and marketing support to increase business opportunities.
* [Product Advertising API](http://docs.aws.amazon.com/AWSECommerceService/latest/GSG/Welcome.html) - Provides access to product data and electronic commerce functionality.

## Credits

Check out the [Credits page](https://github.com/donnemartin/awesome-aws/blob/master/CREDITS.md).

## Other Awesome Lists

Other awesome lists can be found in [awesome](https://github.com/sindresorhus/awesome) and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).

## Contact Info

Feel free to contact me to discuss any issues, questions, or comments.

My contact info can be found on my [GitHub page](https://github.com/donnemartin).

## License

*I am providing code and resources in this repository to you under an open source license.  Because this is my personal repository, the license you receive to my code and resources is from me and not my employer (Facebook).*

    Copyright 2017 Donne Martin

    Creative Commons Attribution 4.0 International License (CC BY 4.0)

    http://creativecommons.org/licenses/by/4.0/

