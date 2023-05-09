# CLOUD-CUSTODIAN PROJECT.
### Prerequisites
Deploying Cloud Custodian involves several steps, including creating an 
- AWS account 
- setting up an AWS IAM user
-  configuring the Custodian policy, and 
-  scheduling the policy to run using AWS Lambda. 

**Here is a high-level overview of the steps involved**:
---
#### 1. Create an AWS account:
*To deploy Cloud Custodian, you will need an AWS account. If you don't already have one, go to the AWS website and create an account *.

#### Set up an AWS IAM user: 
- *Cloud Custodian requires an IAM user with the necessary permissions to access and manage resources in your AWS account*. 
- *You can create a new IAM user specifically for Cloud Custodian, or use an existing user*.
- *You will need to grant the necessary IAM policies to the user to allow them to manage the resources you want to control*.

#### Install Cloud Custodian: 
- *Cloud Custodian can be installed using pip or by downloading the source code from GitHub. Once installed, you can configure it using YAML files*.

#### Configure Custodian policies:
- *Custodian policies are defined in YAML files, which specify the resources you want to control, the actions to take when resources meet the specified criteria, and any exclusion filters*.
-  *You can create custom policies or use the sample policies provided by Custodian*.

#### Schedule the policy to run: 
- *Cloud Custodian policies can be run manually or scheduled to run automatically using AWS Lambda*. 
- *You will need to create a Lambda function, upload the Custodian code and policy files, and configure the function to run on a schedule*.

#### Monitor policy execution:
- *Once you have deployed and scheduled your Custodian policies, you can monitor their execution using CloudWatch Logs and Metrics*.

**Note that this is just a high-level overview, and there may be additional steps or considerations depending on your specific use case. The Cloud Custodian documentation provides more detailed instructions for deploying and configuring Custodian**.