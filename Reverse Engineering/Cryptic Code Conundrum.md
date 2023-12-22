Set Break point on main then jump to secret function

```
┌──(kali㉿kali)-[~/Desktop]
└─$ gdb Payload    
GNU gdb (Debian 13.2-1) 13.2
Copyright (C) 2023 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
Type "show copying" and "show warranty" for details.
This GDB was configured as "x86_64-linux-gnu".
Type "show configuration" for configuration details.
For bug reporting instructions, please see:
<https://www.gnu.org/software/gdb/bugs/>.
Find the GDB manual and other documentation resources online at:
    <http://www.gnu.org/software/gdb/documentation/>.

For help, type "help".
Type "apropos word" to search for commands related to "word"...
Reading symbols from Payload...
(No debugging symbols found in Payload)
(gdb) break main
Breakpoint 1 at 0x8049300
(gdb) run
Starting program: /home/kali/Desktop/Payload 
[Thread debugging using libthread_db enabled]
Using host libthread_db library "/lib/x86_64-linux-gnu/libthread_db.so.1".

Breakpoint 1, 0x08049300 in main ()
(gdb) jump *0x080491ef
Continuing at 0x80491ef.
Flag: KPMG_CTF{19591550c6c64f1fc12593617371939c}
```

```
KPMG_CTF{19591550c6c64f1fc12593617371939c}
```