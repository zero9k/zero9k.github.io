---
layout: default
title: arrays / map_array
---

Version: e36f9fe




### NAME
    map_array() - modify an array of elements via application of a function


### SYNOPSIS
    mixed *map_array( mixed *arr, string fun, object ob,
    mixed extra, ... );
    mixed *map_array( mixed *arr, function f, mixed extra, ... );


### DESCRIPTION
    Returns  an array holding the items of 'arr' mapped through either with
    that element as a parameter. A second parameter 'extra' is sent in each
    call if given.  Principal function:

    foreach (index) arr[index] = ob->fun(arr[index],extra);

    The value returned by 'ob->fun(arr[.index.], extra)' replaces the existing
    element in the array. If 'arr' is not an array, then 0 will be returned.


### SEE ALSO
    filter_array(3), sort_array(3), map(3)



