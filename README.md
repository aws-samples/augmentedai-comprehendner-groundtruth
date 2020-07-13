## Easily setup built-in human review loops for NLP based entity recognition workflows using Amazon SageMaker Ground Truth, Amazon Comprehend and Amazon Augmented AI

### Introduction

Amazon A2I provides built-in human review workflows for common machine learning use cases, such as NLP based entity recognition from documents, which allows predictions from Amazon Comprehend AutoML to be reviewed easily. You can also create your own workflows for ML models built on Amazon SageMaker or any other tools. Using Amazon A2I, you can allow human reviewers to step in when a model is unable to make a high confidence prediction or to audit its predictions on an on-going basis. Learn more <a href="https://aws.amazon.com/augmented-ai/">here</a>

We provide you two notebooks in this repo to demonstrate integration of Amazon Augmented AI with Amazon Comprehend for two example use cases:

### Use Case 1 - Setup human review of Amazon Comprehend Entity Detection low confidence predictions with Amazon Augmented AI
We will setup 

### Use Case 2 - Setup human review of NLP based Custom Entity Recognition workflows with Amazon SageMaker Ground Truth, Amazon Comprehend AutoML and Amazon Augmented AI (A2I)
In this notebook, we will first setup a NLP based workflow for custom entity recognition by <a href="https://docs.aws.amazon.com/comprehend/latest/dg/custom-entity-recognition.html">Amazon Comprehend</a> from an input document using a labeled dataset created by <a href="https://docs.aws.amazon.com/sagemaker/latest/dg/sms-named-entity-recg.html">Amazon SageMaker Ground Truth Named Entity Recognition</a>. We will then show how you can set up an Amazon A2I human loop with a flow definition to trigger a review task for low confidence predictions. Please navigate to the notebook <a href="">SageMakerGT-ComprehendNER-A2I-Notebook</a> to get started

For more in depth instructions, visit https://docs.aws.amazon.com/sagemaker/latest/dg/a2i-getting-started.html

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

