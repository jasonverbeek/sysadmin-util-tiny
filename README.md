# sysadmin-util-tiny
scripts that might be usefull for different ranges of work on linux machines.

**only requires python3**

## scripts
### gateway
get current gateway(s)

`$ gateway`

```
wlo1 192.168.2.254
eno1 10.0.10.254
```
get current gateway for a specific interface

`$ gateway [-i/--interface] eno1`
```
eno1 10.0.10.254
```
## credits

from [sysadmin-util.git](https://github.com/skx/sysadmin-util):
- the concept of a `gateway` command.
