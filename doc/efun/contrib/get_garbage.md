---
layout: default
title: contrib / get_garbage.pre
---

Version: e36f9fe

object *get_garbage();

returns array of all (up to __MAX_ARRAY_SIZE__) those cloned(!) objects which
have neither environment nor inventory  and aren't shadowing another object
and haven't object->super set
