# AdaSPIR-V

This is an Ada 2012 library that implements the enumerations for the [SPIR-V](https://www.khronos.org/registry/spir-v)
intermediate language by Khronos. This library can be used to build tools that manipulate SPIR-V in Ada 2012.

This has not been tested out yet, so any comments, suggestions, bugs, please add an issue.

# Building

## GNAT

I have built this using the following commands on Linux.

```
$ cd build/gnat
$ SPIRV_MODE=debug make
```

# Dependencies

Ada 2012 compiler.

## Tested with

FSF GNAT 4.9.2

# Author

Luke A. Guest

# Licence

New-style BSD, see LICENCE file in source root directory and at the start of all source files.
