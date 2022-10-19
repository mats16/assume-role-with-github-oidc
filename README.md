# Assume Role with GitHub OpenID Connect

## Huw to use

### 1. Add oidc provider to your AWS account

Deploy [github-oidc-provider.yaml](./github-oidc-provider.yaml)

[![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][oidc-provider]

[oidc-provider]: https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?stackName=github-oidc-provider&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/github-oidc-provider.yaml

### 2. Add role for github actions

| Role | Description | Launth |
|:--|:--|:--|
| public-image-publishing | Publish docker image to ECS Public | [![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][public-image-publishing] |
| file-publishing | Publish static files to S3 Bucket | [![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][file-publishing] |
| cdk-deploy | CDK Deploy | [![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][cdk-deploy] |
| cdk-assets-publishing | Publish CDK assets to S3 Bucket | [![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][cdk-assets-publishing] |
| sam-publishing | Publish SAM Application | [![launch-stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)][sam-publishing] |


[public-image-publishing]: https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?stackName=github-actions-public-image-publishing&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-public-image-publishing.yaml
[file-publishing]: https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?stackName=github-actions-file-publishing&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-file-publishing.yaml
[cdk-deploy]: https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?stackName=github-actions-cdk-deploy&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-cdk-deploy.yaml
[cdk-assets-publishing]: https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?stackName=github-actions-cdk-assets-publishing&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-cdk-assets-publishing.yaml
[sam-publishing]: https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?stackName=github-actions-sam-publishing&templateURL=https://s3.amazonaws.com/mats-toolbox/assume-role-with-github-oidc/latest/roles/github-actions-sam-publishing.yaml
