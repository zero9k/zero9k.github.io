---
layout: default
title: interactive / resolve
---

Version: e36f9fe




### NAME
    resolve() - resolve an internet address to domain name, or vice versa


### SYNOPSIS
    int resolve( string address, string callback_func );


### DESCRIPTION
    resolve()  resolves  'address',  which should be an internet address in
    the form "127.0.0.1" or a domain name, into its domain name, or  inter‐
    net  address.   When  the  resolve is complete, 'callback_func' will be
    called in the current object.  The form of the callback is:

    void callback(string address, string resolved, int key);

    decimal ip address.  The unknown value will be 0 if the lookup failed.


### SEE ALSO
    query_host_name(3), socket_address(3), query_ip_name(3),  query_ip_num‐
    ber(3)



