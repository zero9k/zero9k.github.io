---
layout: default
title: objects / new
---

Version: e36f9fe




### NAME
    new() - load a copy of an object


### SYNOPSIS
    object new( string name );


### DESCRIPTION
    Load  a  new  object  from  definition <name>, and give it a new unique
    name.  Returns the new object.  An object with a nonzero  environment()
    cannot be cloned.


### SEE ALSO
    clone_object(3), destruct(3), move_object(3)


