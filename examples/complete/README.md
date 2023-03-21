## Sonarqube Examples
![squareops_avatar]

[squareops_avatar]: https://squareops.com/wp-content/uploads/2022/12/squareops-logo.png

### [SquareOps Technologies](https://squareops.com/) Your DevOps Partner for Accelerating cloud journey.
<br>
This example will be very useful for users who are new to a module and want to quickly learn how to use it. By reviewing the examples, users can gain a better understanding of how the module works, what features it supports, and how to customize it to their specific needs.
<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_sonarqube"></a> [sonarqube](#module\_sonarqube) | ../../ | n/a |

## Resources

| Name | Type |
|------|------|
| [aws_eks_cluster.cluster](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/eks_cluster) | data source |
| [aws_eks_cluster_auth.cluster](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/eks_cluster_auth) | data source |

## Inputs

No inputs.

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_hostname"></a> [hostname](#output\_hostname) | URL for sonarqube |
| <a name="output_password"></a> [password](#output\_password) | Initial password for sonarqube |
| <a name="output_postgresql_password"></a> [postgresql\_password](#output\_postgresql\_password) | password for postgresql deployed with sonarqube |
| <a name="output_postgresql_username"></a> [postgresql\_username](#output\_postgresql\_username) | username for postgresql deployed with sonarqube |
| <a name="output_username"></a> [username](#output\_username) | Initial username for sonarqube |
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->