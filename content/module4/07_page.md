---
title: "Replace this section with the following code:"
date: 2020-10-21T11:44:34+03:00
weight: 07
draft: false
---

```
- promotions-manager-api:      
      depends_on: 
        - promotions-manager-docdb
      input_values:
        - API_PORT: $API_PORT
        - AWS_INSTANCE_TYPE: $AWS_INSTANCE_TYPE
        - DATABASE_HOST: $outputs.promotions-manager-docdb.connection_string
        - RELEASE_NUMBER: $RELEASE_NUMBER
        - API_BUILD_NUMBER: $API_BUILD_NUMBER
  
services:
  - promotions-manager-docdb:
      input_values:
        - USERNAME: $DB_USERNAME
        - PASSWORD: $DB_PASSWORD
        - SANDBOX_ID: ${SandboxID}

debugging:
  availability: on
```
