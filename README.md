# Processing CloudTrail Logs with AWS Lambda

This serverless application creates the necessary resources and integrations for properly enabling and processing CloudTrail logs in your environment. The below architecture showcases how logs are stored, post-processed, and push to Elasticsearch.

## Architecture

![Log-Architecture](images/aws-ct-processing-arch.png)

## Prerequisites

Below are the necessary prerequisites:

*	[pip](https://pip.pypa.io/en/stable/installing/)
*	[Serverless Framework](https://serverless.com/)
*	[AWS Account](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/)

## Install Dependencies

After cloning the repo, change to the aws-ct-processing directory and run the following to install the dependencies:

```
pip install -r requirements.txt -t ./
```

> If you are using Mac OS X and installed Python using Homebrew, you'll need to add a setup.cfg in the aws-ct-processing directory with the following:

```
[install]
prefix=
```

## Deploy



## Access