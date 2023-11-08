+++
title = 'My First Post'
date = 2023-11-08T22:57:57+07:00
draft = false
+++
## Introduction

This is **bold** text, and this is *emphasized* text.

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

```javascript
resource "aws_vpc" "main" {
  cidr_block = "10.0.0.0/16"
}
```

Another Golang block

```go
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```

Visit the [Hugo](https://gohugo.io) website!