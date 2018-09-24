---
layout: default
title: general / nullp
---

Version: e36f9fe




### NAME
    nullp() - determine whether or not a given variable is null.


### SYNOPSIS
    int nullp( mixed arg );


### DESCRIPTION
    Return 1 if 'arg' is null.  'arg' will be null in the following cases:

    1.     it has not yet been initialized.

    2.     it points to a destructed object.

    3.     it  is a function (formal) parameter that corresponds to a miss‐
    ing actual argument.


### SEE ALSO
    mapp(3),  stringp(3),  pointerp(3),  objectp(3),  intp(3),  bufferp(3),
    floatp(3), functionp(3), undefinedp(3), errorp(3)



