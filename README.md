# EKS Cluster setup with multiple IAC solutions

This is an example of how to provision EKS cluster with AWS CDK, Terraform CDK, Pulumi, Terraform, CloudFromation and ClusterAPI.


## Architecture Outline

Our cluster is comprised out of the following components:

- Dedicated VPC.
- EKS Cluster.
- AutoScalingGroup of on-demand instances that are used as the EKS self-managed nodes.
- Dedicated IAM Role for the AutoScalingGroup.

