---
title: cd
categories: |
  filesystem
version: 0.85.0
filesystem: |
  Change directory.
usage: |
  Change directory.
---
<!-- This file is automatically generated. Please edit the command in https://github.com/nushell/nushell instead. -->

# <code>{{ $frontmatter.title }}</code> for filesystem

<div class='command-title'>{{ $frontmatter.filesystem }}</div>

## Signature

```> cd {flags} (path)```

## Parameters

 -  `path`: the path to change to


## Input/output types:

| input   | output  |
| ------- | ------- |
| nothing | nothing |
| string  | nothing |
## Examples

Change to your home directory
```nu
> cd ~

```

Change to a directory via abbreviations
```nu
> cd d/s/9

```

Change to the previous working directory ($OLDPWD)
```nu
> cd -

```
