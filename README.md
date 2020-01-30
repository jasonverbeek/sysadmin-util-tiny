# sysadmin-util-tiny
scripts that might be usefull for different ranges of work on \*nix machines.

**only requires python3**

## scripts
### gateway _\[options\]_
get current gateway(s)

`$ gateway`

```
wlo1 192.168.2.254
eno1 10.0.10.254
```
- `-h` `--help` Show help and exit
- `-i<interface>` `--interface <interface>` Show details for a single network interface

### passgen _\<length\> \[options\]_
generate a password

`$ passgen 16`
```
OZF#x`ObS%nx<Rf,
```
- `-h` `--help` Show help and exit
- `-s` `--no-special` Excludes special characters from the generated password
- `-n` `--no-numeric` Excludes numeric characters from the generated password
- `-a` `--no-alphabetical` Excludes alphabetical characters from the generated password
