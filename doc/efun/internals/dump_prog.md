---
layout: default
title: internals / dump_prog
---

Version: e36f9fe




### NAME
    dump_prog() - dump/disassemble an LPC object


### SYNOPSIS
    void dump_prog( object ob, int flags default: 0, string file );


### DESCRIPTION
    dump_prog()  dumps  information  about  the program of 'obj' to a file,
    does not have write access to the file, it fails.

    Flags can be a combination of the following values: 1 - include a  dis‐
    assembly of the i-code 2 - include line number information


### SEE ALSO
    debug_info(3), dumpallobj(3)



