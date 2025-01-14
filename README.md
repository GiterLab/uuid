# uuid

The uuid package generates and inspects UUIDs based on
[RFC 4122](https://datatracker.ietf.org/doc/html/rfc4122)
and DCE 1.1: Authentication and Security Services.

This package is based on the github.com/pborman/uuid package (previously named
code.google.com/p/go-uuid).  It differs from these earlier packages in that
a UUID is a 16 byte array rather than a byte slice.  One loss due to this
change is the ability to represent an invalid UUID (vs a NIL UUID).

## Install

```sh
go get github.com/GiterLab/uuid for v1
go get github.com/GiterLab/uuid/v2 for v2
```

## Mark

```text
forked from code.google.com/p/go-uuid/uuid  v1.x.x
forked from github.com/google/uuid v2.x.x
```
