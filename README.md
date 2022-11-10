# Create aws CE2 instance with terraform

## project structure

```
.
├── instance_ec2
│   ├── main.tf
│   └── terraform.tfstate.backup
└── README.md

1 directory, 3 files
```

## Commands to create an instance

```
terraform init
```

![terraform init"](resources/img-1.jpeg)

```
terraform plan -out=tfplan
```

![terraform plan -out=tfplan"](resources/img-2.jpeg)

```
terraform apply
```


![terraform apply"](resources/img-3.jpeg)

When the above commands are executed the following files will be created:

<br>

![When the above commands are executed the following files will be created"](resources/img-4.jpeg)

Now we can see in aws platform our created instance:

<br>

![Now we can see in aws platform our created instance"](resources/img-7.jpeg)

## Delete the CE2 instance

```
terraform destroy --auto-approve
```

![terraform destroy --auto-approve"](resources/img-5.jpeg)

![terraform destroy --auto-approve"](resources/img-6.jpeg)

![terraform destroy --auto-approve"](resources/img-8.jpeg)