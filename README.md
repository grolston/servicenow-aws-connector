# ServiceNow AWS Connector

A CloudFormation template to deploy the ServiceNow AWS Connector. Permissions reference [ServiceNow AWS Baseline Permissions](https://docs.aws.amazon.com/servicecatalog/latest/adminguide/baseline-permissions.html).

The template creates 2 IAM users and 1 role. The IAM users are created with only programmatic access via API key. These keys are stored in Secrets Manager which you will need to retrieve the values from to put into ServiceNow.
