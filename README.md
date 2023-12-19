# Dynamic Annotation for Rhombus

## SYNOPSIS

Adds a `Dyn` annotation that selectively removes static information. Makes [Static Rhombus](https://docs.racket-lang.org/rhombus/static-lib.html) a gradually typed language.

```rhombus
#lang rhombus/static

import:
  rhombus_dyn open

fun get_len(lst :: Dyn):
  lst.length()
```
## DESCRIPTION

This is a little research proof-of-concept to see how far we can push Rhombus's macro and static information system. This is not intended for serious production use.

## INSTALLATION

This package is not in the Racket/Rhombus package repository. Therefore, the easiest way to install this package is to clone the repository and install it directly with `raco` from the command line like so:

```bash
git clone https://github.com/ashton314/rhombus_dyn.git
cd rhombus_dyn
raco pkg install
```

## LICENSE

MIT

## BUGS

Feel free to report bugs [here on GitHub](https://github.com/ashton314/rhombus_dyn/issues). No promises on whether or not I'll look at them—this is a research POC and not intended for any production usage.

## AUTHORS

 - [Ashton Wiersdorf](https://lambdaland.org)
