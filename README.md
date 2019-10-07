# AWS AMI for CSYE 6225

## Team Information

| Name | NEU ID | Email Address |
| --- | --- | --- |
| Abhinn Ankit| 001837913 | ankit.a@husky.neu.edu |
| Anish Surti| 001814243 | surti.a@husky.neu.edu |
| Srikant Swamy | 001212307 | swamy.sr@husky.neu.edu |
| Nilank Sharma | 001279669 | sharma.nil@husky.neu.edu |

## Validate Template

```
packer validate centos-ami-template.json
```

## Build AMI

```
packer build -var 'aws_region=us-east-1' centos-ami-template.json
```
