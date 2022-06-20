# Assume Role with GitHub OpenID Connect

## Huw to use

### 1. Add oidc provider to your AWS account

Deploy [github-oidc-provider.yaml](./github-oidc-provider.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][1]

[1]: https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-oidc-provider&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/github-oidc-provider.yaml

### 2. Add role for github actions

#### CDK deploy

[roles/github-actions-cdk-deploy.yaml](./roles/github-actions-cdk-deploy.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][2]

[2]: https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-cdk-deploy&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-cdk-deploy.yaml

#### File publishing to S3

[roles/github-actions-file-publishing.yaml](./roles/github-actions-file-publishing.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][3]

[3]: https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-file-publishing&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-file-publishing.yaml

#### SAM publishing

[roles/github-actions-sam-publishing.yaml](./roles/github-actions-sam-publishing.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][4]

[4]: https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=github-actions-sam-publishing&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-sam-publishing.yaml
