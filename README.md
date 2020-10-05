# Introduction to Amazon Fraud Detector

[Amazon Fraud Detector](https://aws.amazon.com/fraud-detector/) is a fully managed service which automates the time consuming and expensive steps to build, train, and deploy an ML model for fraud detection - making it easier for users to leverage the technology.

This repository demonstrates how to use Amazon Fraud Detector through interactive [Jupyter notebooks](https://jupyter.org/) and the AWS SDK for Python, [Boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html).

[FraudDetector_intro.ipynb](FraudDetector_intro.ipynb) demonstrates all the basic steps in order to create a ML fraud detection model, integrate it with a Detector, add business rules and get some predictions.

To run through the notebook in your own AWS account, you can click one of the CloudFormation deploy links below, which will launch an [Amazon SageMaker Notebook Instance](https://docs.aws.amazon.com/sagemaker/latest/dg/nbi.html) and copy this repository into it:

| Region                       | Deploy Link |
|:-----------------------------|:------------|
| `ap-southeast-1` (Singapore) | [![Launch Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=FraudDetectorPoC&templateURL=https://public-asean-ml-pocs-ap-southeast-1.s3-ap-southeast-1.amazonaws.com/fraud-detector/FraudDetectorPoC.yaml) |
| `us-east-1` (US N. Virginia) | [![Launch Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=FraudDetectorPoC&templateURL=https://public-asean-ml-pocs-us-east-1.s3.amazonaws.com/fraud-detector/FraudDetectorPoC.yaml) |

Once the stack is launched, you can open your notebook from the [Amazon SageMaker console](https://console.aws.amazon.com/sagemaker/home?#/notebook-instances) and start exploring!


## Further Resources

You can find more information about Amazon Fraud Detector at:

- The service's [product page](https://aws.amazon.com/fraud-detector/)
- The official [samples repository on GitHub](https://github.com/aws-samples/aws-fraud-detector-samples)
- The [Amazon Fraud Detector docs](https://docs.aws.amazon.com/frauddetector/latest/ug/what-is-frauddetector.html)
