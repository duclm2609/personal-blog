+++
title = 'IAM role for service accounts on EKS'
date = 2024-01-07T13:36:00+07:00
draft = false
+++
## Introduction

This is **bold** text, and this is *emphasized* text.

{{< youtube Pn7cVrUzp6Q >}}

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: nginx-deployment
  labels:
    app: nginx
spec:
  replicas: 3
  selector:
    matchLabels:
      app: nginx
  template:
    metadata:
      labels:
        app: nginx
    spec:
      containers:
      - name: nginx
        image: nginx:1.14.2
        ports:
        - containerPort: 80
```

This is Terraform code

{{< highlight tf >}}
module "vpc" {
  source = "terraform-aws-modules/vpc/aws"

  name = "my-vpc"
  cidr = "10.0.0.0/16"

  azs             = ["eu-west-1a", "eu-west-1b", "eu-west-1c"]
  private_subnets = ["10.0.1.0/24", "10.0.2.0/24", "10.0.3.0/24"]
  public_subnets  = ["10.0.101.0/24", "10.0.102.0/24", "10.0.103.0/24"]

  enable_nat_gateway = true
  enable_vpn_gateway = true

  tags = {
    Terraform = "true"
    Environment = "dev"
  }
}
{{< / highlight >}}


Another Golang block

```go
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```

Visit the [Hugo](https://gohugo.io) website!