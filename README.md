# How to use the external secret to mount secrets to Kubernetes pods from AWS Secrets Manager?

External Secrets Operator is a Kubernetes operator that integrates external secret management systems like AWS Secrets Manager, HashiCorp Vault, Google Secrets Manager, Azure Key Vault, IBM Cloud Secrets Manager, CyberArk Conjur, and many more. The operator reads information from external APIs and automatically injects the values into a Kubernetes Secret.

Secrets are a substantial part of our applications, but their management could be a hassle. We want to follow GitOps principles, yet we can’t have them plain-text stored in our Git repository or even base64 encoded as Kubernetes secrets are. We’re already in the cloud and would like to leverage our cloud’s secrets management system, however, we might have multi-cloud deployment in the future.

![1](https://github.com/Dhruvin4530/k8s-external-secrets/blob/main/1.png)

To read the detailed overview click [here](https://medium.com/@dksoni4530/how-to-use-the-external-secrets-to-mount-secrets-to-kubernetes-pods-from-aws-secrets-manager-ad87e4e9e4a9).

