# hexer

fast converter from binary to hexadecimal.

Found on [stackoverflow](http://stackoverflow.com/a/3771421).

```erlang
1> hexer:bin_to_hex(<<"\272\263N">>).
<<"BAB34E">>
2> hexer:md5(<<"foo">>).
<<"ACBD18DB4CC2F85CEDEF654FCCC4A4D8">>
```
