# CVE-2017-5123
Exploit for the kernel vulnerability CVE-2017-5123

You can compile it with: `gcc -static -Wall -Wextra -Werror -o cve20175123 CVE-2017-5123.c`

If you want further explanation, I've wrote an article explaining how it's work, you can find it [here](http://pwn.beers4flags.fr/exploit/kernel-cve-2017-5123/)

This exploit is more reliable than the previous published by hexpresso, but it's still not perfect, he won't work on system with SMEP/SMAP and with kptr_restrict.
