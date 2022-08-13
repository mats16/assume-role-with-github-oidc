# Assume Role with GitHub OpenID Connect

## Huw to use

### 1. Add oidc provider to your AWS account

Deploy [github-oidc-provider.yaml](./github-oidc-provider.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][1]

[1]: https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-oidc-provider&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/github-oidc-provider.yaml

### 2. Add role for github actions

#### Docker image publishing to ECR Public

[roles/github-actions-public-image-publishing.yaml](./roles/github-actions-public-image-publishing.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-public-image-publishing&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-public-image-publishing.yaml)

#### File publishing to S3

[roles/github-actions-file-publishing.yaml](./roles/github-actions-file-publishing.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-file-publishing&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-file-publishing.yaml)

#### CDK deploy

[roles/github-actions-cdk-deploy.yaml](./roles/github-actions-cdk-deploy.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-cdk-deploy&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-cdk-deploy.yaml)

#### CDK assets publishing to multi-region S3

[roles/github-actions-cdk-assets-publishing.yaml](./roles/github-actions-cdk-assets-publishing.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-cdk-assets-publishing&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-cdk-assets-publishing.yaml)

#### SAM publishing

[roles/github-actions-sam-publishing.yaml](./roles/github-actions-sam-publishing.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-sam-publishing&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-sam-publishing.yaml)
