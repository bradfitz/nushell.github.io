---
title: dfr into-nu
categories: |
  dataframe
version: 0.84.0
dataframe: |
  Converts a dataframe or an expression into into nushell value for access and exploration.
usage: |
  Converts a dataframe or an expression into into nushell value for access and exploration.
---

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> dfr into-nu --rows --tail```

## Parameters

 -  `--rows {number}`: number of rows to be shown
 -  `--tail` `(-t)`: shows tail rows


## Input/output types:

| input | output |
| ----- | ------ |
| any   | any    |

## Examples

Shows head rows from dataframe
```shell
> [[a b]; [1 2] [3 4]] | dfr into-df | dfr into-nu
╭───┬───┬───╮
│ # │ a │ b │
├───┼───┼───┤
│ 0 │ 1 │ 2 │
│ 1 │ 3 │ 4 │
╰───┴───┴───╯

```

Shows tail rows from dataframe
```shell
> [[a b]; [1 2] [5 6] [3 4]] | dfr into-df | dfr into-nu -t -n 1
╭───┬───┬───╮
│ # │ a │ b │
├───┼───┼───┤
│ 2 │ 3 │ 4 │
╰───┴───┴───╯

```

Convert a col expression into a nushell value
```shell
> dfr col a | dfr into-nu
╭───────┬────────╮
│ expr  │ column │
│ value │ a      │
╰───────┴────────╯
```


**Tips:** Dataframe commands were not shipped in the official binaries by default, you have to build it with `--features=dataframe` flag