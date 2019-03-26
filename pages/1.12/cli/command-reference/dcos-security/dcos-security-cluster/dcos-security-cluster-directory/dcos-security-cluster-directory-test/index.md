---
layout: layout.pug
navigationTitle:  dcos security cluster directory test
title: dcos security cluster directory test
menuWeight: 40
excerpt: Testing a connection to an LDAP backend
enterprise: true
---
# Description

The `dcos security cluster directory test` command tests a connection to the LDAP backend. With this command, you can perform basic test and verify that the current directory (LDAP) configuration parameters allow for a successful connection to the directory backend. For instance, this endpoint simulates the procedure for authentication via LDAP, but provides more useful feedback upon failure than the actual login endpoint.

# Usage

```
dcos security cluster directory test [OPTIONS] UID PASSWORD
```

# Options

| Name | Description |
| `-j`, `--json` |  Output data in JSON format.|
| `-h`, `--help` |  Show this message and exit. |


## Positional Arguments

| Name | Description |
| `UID` | User ID (Required) |
| `PASSWORD` | Password for UID.|

