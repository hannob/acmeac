acmeac
======

Script to manage ACME accounts

This is a script I wrote for myself to access some basic ACME account management
functionality.

Example usage
-------------

```
acmeac info example.key
```

Shows account id and information about the ACME account associated with
example.key.

This can be useful to get access to the account id in order to implement
[ACME-CAA (RFC 8657)](https://www.rfc-editor.org/rfc/rfc8657).

```
acmeac deleteaccount example.key
```

This deletes the ACME account associated with the key in example.key.

who
---

Written by [Hanno Böck](https://itsec.hboeck.de).
