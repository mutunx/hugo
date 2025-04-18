---
title: hugo.Environment
description: Returns the current running environment.
categories: []
keywords: []
params:
  functions_and_methods:
    aliases: []
    returnType: string
    signatures: [hugo.Environment]
---

The `hugo.Environment` function returns the current running [environment](g) as defined through the `--environment` command line flag.

```go-html-template
{{ hugo.Environment }} → production
```

Command line examples:

Command|Environment
:--|:--
`hugo`|`production`
`hugo --environment staging`|`staging`
`hugo server`|`development`
`hugo server --environment staging`|`staging`
