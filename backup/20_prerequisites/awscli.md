---
title: "Update to the latest AWS CLI"
chapter: false
weight: 45
draft: true
comment: default install now includes aws-cli/1.15.83
hidden: true
---

{{% notice tip %}}
For this workshop, please ignore warnings about the version of pip being used.
{{% /notice %}}

1. Run the following command to view the current version of aws-cli:
```
aws --version
```

2. Update to the latest version:
```
pip install --user --upgrade awscli
```

3. Confirm you have a newer version:
```
aws --version
```
