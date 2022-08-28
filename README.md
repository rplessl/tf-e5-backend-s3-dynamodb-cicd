# tf-e5-backend-s3-dynamodb-cicd
Learn Terraform Exercise using guardrails and hints


[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

Goals of this Exercise:

- [ ] Create a terraform backend based on S3 and DynamoDB
- [ ] Adapt a simple CI/CD Workflow

## 🚧 -> 🚀

Terraform workflow:

```
terraform fmt
terraform init
terraform validate
terraform plan -out my-tf-plan.tfplan
terraform apply my-tf-plan.tfplan
terraform destroy
```

## step by step

### step 1
- [ ] create a default file set
- [ ] adapt https://angelo-malatacca83.medium.com/aws-terraform-s3-and-dynamodb-backend-3b28431a76c1 to your setup
- [ ] Goal 1: Terraform State is stored in S3 (and DynamoDB); check and prove that this is correct

### step 2
- [ ] Implement a simple CI/CD Environment




---

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg