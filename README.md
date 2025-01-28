# Terraform Playground Module

This Terraform module performs basic math operations (sum and difference) on two input numbers.

## Usage

```hcl
module "myPlayground" {
  source  = "Frunza/terraform-registry-playground"
  version = "0.0.2"

  number1 = 8
  number2 = 3
}
