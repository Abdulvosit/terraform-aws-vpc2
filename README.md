# terraform-aws-vpc Module
### Usage:
```
module "vpc" {
    source = "Abdulvosit/vpc2/aws"
    cidr_block = "10.0.0.0/16"
    tags = {
        Name = "Dev"
    }
}
```