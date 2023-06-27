# mitm
Tool for mitm (for linux)

### Descriptiom
Python + bash tool for doing arpsoopf

### Usage
mitm.py -i {interface}

Set interface to sniff

### DLC for bash
apt install dsniff nmap -y

### Usage

-i --- specifies the interface to sniff
-f --- file to write result of sniffing

> You can start mitm without -f

``` shell
mitm.py -i eth0
# scan targets in eth0
# result of sniff is saved in test.out
```

``` shell
mitm.py -i eth0 -f /path/to/out_file.out
# scan targets in eth0
# result of sniff is saved in /path/to/out_file.out
```
