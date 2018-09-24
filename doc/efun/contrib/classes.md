---
layout: default
title: contrib / classes.pre
---

Version: e36f9fe

mixed *classes(object, int default : 0);

returns:
int == 0: array consisting of names of classes used by object
int != 0:
({
    ({
    "class_name",
    ({
    "member_name",
    "type"
    }),
    ...
    }),
    ...
})
