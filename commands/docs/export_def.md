---
title: export def
categories: |
  core
version: 0.84.0
core: |
  Define a custom command and export it from a module.
usage: |
  Define a custom command and export it from a module.
---

# <code>{{ $frontmatter.title }}</code> for core

<div class='command-title'>{{ $frontmatter.core }}</div>

## Signature

```> export def (name) (params) (block)```

## Parameters

 -  `name`: definition name
 -  `params`: parameters
 -  `block`: body of the definition


## Input/output types:

| input   | output  |
| ------- | ------- |
| nothing | nothing |

## Examples

Define a custom command in a module and call it
```shell
> module spam { export def foo [] { "foo" } }; use spam foo; foo
foo
```

## Notes
This command is a parser keyword. For details, check:
  https://www.nushell.sh/book/thinking_in_nu.html