makeheaders
===========

 > A clib package for the `makeheaders` command  (**original:** http://www.hwaci.com/sw/mkhdr/)

## Installation

```sh
clib install makeheaders
```

## Usage

```
Usage: makeheaders [options] filename...
Options:
  -h          Generate a single .h to standard output.
  -H          Like -h, but only output EXPORT declarations.
  -v          (verbose) Write status information to the screen.
  -doc        Generate no header files.  Instead, output information
              that can be used by an automatic program documentation
              and cross-reference generator.
  -local      Generate prototypes for "static" functions and
              procedures.
  -f FILE     Read additional command-line arguments from the file named
              "FILE".
  --          Treat all subsequent comment-line parameters as filenames,
              even if they begin with "-".
```
