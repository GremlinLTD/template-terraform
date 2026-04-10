# terraform-PROVIDER-NAME

> Replace this with your module description.

## Usage

```hcl
module "example" {
  source  = "gremlinltd/NAME/PROVIDER"
  version = "~> 1.0"

  # example = "value"
}
```

## Requirements

| Name      | Version |
| --------- | ------- |
| terraform | >= 1.5  |

## Inputs

<!-- TODO: Document inputs -->

## Outputs

<!-- TODO: Document outputs -->

## Development

```sh
git clone https://github.com/gremlinltd/REPO_NAME.git
cd REPO_NAME
terraform init
terraform validate
```

## After creating a repo from this template

1. Rename the repo to `terraform-<provider>-<name>` (Terraform registry convention)
2. Replace `REPO_NAME` in `cog.toml`, `cliff.toml`, `sonar-project.properties`, `CONTRIBUTING.md`, and this README
3. Uncomment and configure the provider in `versions.tf`
4. Set up SonarCloud project and add `SONAR_TOKEN` as a repo secret
5. Update this README with actual module docs
