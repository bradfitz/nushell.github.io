---
title: math
categories: |
  math
version: 0.84.0
math: |
  Use mathematical functions as aggregate functions on a list of numbers or tables.
usage: |
  Use mathematical functions as aggregate functions on a list of numbers or tables.
---

# <code>{{ $frontmatter.title }}</code> for math

<div class='command-title'>{{ $frontmatter.math }}</div>

## Signature

```> math ```


## Input/output types:

| input   | output |
| ------- | ------ |
| nothing | string |

## Notes
You must use one of the following subcommands. Using this command as-is will only produce this help message.

## Subcommands:

| name                                               | type    | usage                                                                                 |
| -------------------------------------------------- | ------- | ------------------------------------------------------------------------------------- |
| [`math abs`](/commands/docs/math_abs.md)           | Builtin | Returns the absolute value of a number.                                               |
| [`math arccos`](/commands/docs/math_arccos.md)     | Builtin | Returns the arccosine of the number.                                                  |
| [`math arccosh`](/commands/docs/math_arccosh.md)   | Builtin | Returns the inverse of the hyperbolic cosine function.                                |
| [`math arcsin`](/commands/docs/math_arcsin.md)     | Builtin | Returns the arcsine of the number.                                                    |
| [`math arcsinh`](/commands/docs/math_arcsinh.md)   | Builtin | Returns the inverse of the hyperbolic sine function.                                  |
| [`math arctan`](/commands/docs/math_arctan.md)     | Builtin | Returns the arctangent of the number.                                                 |
| [`math arctanh`](/commands/docs/math_arctanh.md)   | Builtin | Returns the inverse of the hyperbolic tangent function.                               |
| [`math avg`](/commands/docs/math_avg.md)           | Builtin | Returns the average of a list of numbers.                                             |
| [`math ceil`](/commands/docs/math_ceil.md)         | Builtin | Returns the ceil of a number (smallest integer greater than or equal to that number). |
| [`math cos`](/commands/docs/math_cos.md)           | Builtin | Returns the cosine of the number.                                                     |
| [`math cosh`](/commands/docs/math_cosh.md)         | Builtin | Returns the hyperbolic cosine of the number.                                          |
| [`math e`](/commands/docs/math_e.md)               | Builtin | Returns the mathematical constant e (exp(1)/'1 | math exp').                          |
| [`math exp`](/commands/docs/math_exp.md)           | Builtin | Returns e raised to the power of x.                                                   |
| [`math floor`](/commands/docs/math_floor.md)       | Builtin | Returns the floor of a number (largest integer less than or equal to that number).    |
| [`math ln`](/commands/docs/math_ln.md)             | Builtin | Returns the natural logarithm. Base: (math e).                                        |
| [`math log`](/commands/docs/math_log.md)           | Builtin | Returns the logarithm for an arbitrary base.                                          |
| [`math max`](/commands/docs/math_max.md)           | Builtin | Returns the maximum of a list of values, or of columns in a table.                    |
| [`math median`](/commands/docs/math_median.md)     | Builtin | Computes the median of a list of numbers.                                             |
| [`math min`](/commands/docs/math_min.md)           | Builtin | Finds the minimum within a list of values or tables.                                  |
| [`math mode`](/commands/docs/math_mode.md)         | Builtin | Returns the most frequent element(s) from a list of numbers or tables.                |
| [`math pi`](/commands/docs/math_pi.md)             | Builtin | Returns the mathematical constant π.                                                 |
| [`math product`](/commands/docs/math_product.md)   | Builtin | Returns the product of a list of numbers or the products of each column of a table.   |
| [`math round`](/commands/docs/math_round.md)       | Builtin | Returns the input number rounded to the specified precision.                          |
| [`math sin`](/commands/docs/math_sin.md)           | Builtin | Returns the sine of the number.                                                       |
| [`math sinh`](/commands/docs/math_sinh.md)         | Builtin | Returns the hyperbolic sine of the number.                                            |
| [`math sqrt`](/commands/docs/math_sqrt.md)         | Builtin | Returns the square root of the input number.                                          |
| [`math stddev`](/commands/docs/math_stddev.md)     | Builtin | Returns the standard deviation of a list of numbers, or of each column in a table.    |
| [`math sum`](/commands/docs/math_sum.md)           | Builtin | Returns the sum of a list of numbers or of each column in a table.                    |
| [`math tan`](/commands/docs/math_tan.md)           | Builtin | Returns the tangent of the number.                                                    |
| [`math tanh`](/commands/docs/math_tanh.md)         | Builtin | Returns the hyperbolic tangent of the number.                                         |
| [`math tau`](/commands/docs/math_tau.md)           | Builtin | Returns the mathematical constant τ.                                                 |
| [`math variance`](/commands/docs/math_variance.md) | Builtin | Returns the variance of a list of numbers or of each column in a table.               |