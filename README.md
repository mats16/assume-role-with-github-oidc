# Assume Role with GitHub OpenID Connect

## Huw to use

### 1. Add oidc provider to your AWS account

Deploy [github-oidc-provider.yaml](./github-oidc-provider.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-oidc-provider&templateURL=https://s3.amazonaws.com/mats-templates/assume-role-with-github-oidc/latest/github-oidc-provider.yaml)

### 2. Add role for github actions

#### CDK deploy

[github-actions-cdk-deploy.yaml](./github-actions-cdk-deploy.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-cdk-deploy&templateURL=https://s3.amazonaws.com/mats-templates/assume-role-with-github-oidc/latest/github-actions-cdk-deploy.yaml)

#### File publishing to S3

[github-actions-file-publishing.yaml](./github-actions-file-publishing.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-file-publishing&templateURL=https://s3.amazonaws.com/mats-templates/assume-role-with-github-oidc/latest/github-actions-file-publishing.yaml)
