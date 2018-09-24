---
layout: default
title: contrib / event.pre
---

Version: e36f9fe

void event(object | object *, string, ...);

calls "event_" + string(...) in:

object *:
each given object

object:
object + (if not destructed) all_inventory(object)
