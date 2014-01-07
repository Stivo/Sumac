**Sumac** is a command line option parser and library.  It tries
to differentiate itself from other libraries by making it dead
simple to define arguments, removing boilerplate and repetition.  It
is a very small, lightweight scala library.

## Purpose

For the original library, go to [quantifind/Sumac](https://github.com/quantifind/Sumac).

This is a small fork to provide shortcuts. If a field is annotated as:

    @Arg(shortcut="c")
    field compression: String = "zip"
    
It can be supplied both as:

    --compression zip
    -c zip
    
This is all. Implementation is not very beautiful, but works.
