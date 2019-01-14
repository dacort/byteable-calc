# Byteable Calc

A simple HTML-based calculator that allows you to easily parse byte strings to human-readable values and do math with them!

## Overview

I often work with file listings (e.g. AWS CLI or HDFS utilities) that output file size in bytes.

I know there are different flags for human-readable output, but sometimes I want to do math with the numbers!

## Usage

1. Open up [index.html](index.html). That's it. Host it somewhere if you like.
2. Enter numbers
3. See human-readable output

For example

|Raw Input|Display Output|
|---|---|
|`233033728`|`222.24 MB`|
|`233033728/250`|`910.29 KB`|
|`250gb/20mb`|`12.50 KB`|

## TODO

- [ ] Use more correct mebibyte syntax (MiB)
- [ ] Allow for mixing of units for calculating rates