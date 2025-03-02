---
title: bits and
categories: |
  bits
version: 0.84.0
bits: |
  Performs bitwise and for integers.
usage: |
  Performs bitwise and for integers.
---

# <code>{{ $frontmatter.title }}</code> for bits

<div class='command-title'>{{ $frontmatter.bits }}</div>

## Signature

```> bits and (target)```

## Parameters

 -  `target`: target integer to perform bit and


## Input/output types:

| input     | output    |
| --------- | --------- |
| int       | int       |
| list\<int\> | list\<int\> |
## Examples

Apply bits and to two numbers
```shell
> 2 | bits and 2
2
```

Apply logical and to a list of numbers
```shell
> [4 3 2] | bits and 2
╭───┬───╮
│ 0 │ 0 │
│ 1 │ 2 │
│ 2 │ 2 │
╰───┴───╯

```


**Tips:** Command `bits and` was not included in the official binaries by default, you have to build it with `--features=extra` flag