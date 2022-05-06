# Assume Role with GitHub OpenID Connect

## Huw to use

### 1. Add oidc provider

Deploy [github-oidc-provider.yaml](./github-oidc-provider.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-oidc-provider&templateURL=https://s3.amazonaws.com/mats-templates/assume-role-with-github-oidc/latest/github-oidc-provider.yaml)

### 2. Add iam role for github actions

For cdk: [github-actions-cdk-deploy.yaml](./github-actions-cdk-deploy.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-cdk-deploy&templateURL=https://s3.amazonaws.com/mats-templates/assume-role-with-github-oidc/latest/github-actions-cdk-deploy.yaml)
