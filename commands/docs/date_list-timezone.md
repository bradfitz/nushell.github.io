---
title: date list-timezone
categories: |
  date
version: 0.84.0
date: |
  List supported time zones.
usage: |
  List supported time zones.
---

# <code>{{ $frontmatter.title }}</code> for date

<div class='command-title'>{{ $frontmatter.date }}</div>

## Signature

```> date list-timezone ```


## Input/output types:

| input   | output |
| ------- | ------ |
| nothing | table  |

## Examples

Show timezone(s) that contains 'Shanghai'
```shell
> date list-timezone | where timezone =~ Shanghai
╭───┬───────────────╮
│ # │   timezone    │
├───┼───────────────┤
│ 0 │ Asia/Shanghai │
╰───┴───────────────╯

```
