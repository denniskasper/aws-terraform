# aws-terraform

Repository to manage AWS infrastructure for multiple environments.

## workspaces

This configuration provisions a single workspace in Terraform Cloud, linked to a specific organization and project. The workspace is managed as code and includes environment variables to enable AWS authentication using Terraform Cloud's Workload Identity feature. This setup ensures secure authentication during runs.

TODO: Extend the configuration to support creating multiple workspaces dynamically.
