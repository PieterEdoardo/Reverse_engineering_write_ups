# S3c_Cult's Schizo write up
https://crackmes.one/crackme/698f40f1e2ba6023bfacaa82


```
~/Projects/RE/crackmes.one/schizo
❯ file ./schizo
./schizo: ELF 64-bit LSB pie executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, BuildID[sha1]=483f9ce7811081202bc5e913598b11d2d9a3537d, for GNU/Linux 4.4.0, not stripped

~/Projects/RE/crackmes.one/schizo
❯ ldd ./schizo
        linux-vdso.so.1 (0x00007f06cd410000)
        libcrypto.so.3 => /usr/lib/libcrypto.so.3 (0x00007f06ccc00000)
        libstdc++.so.6 => /usr/lib/libstdc++.so.6 (0x00007f06cc800000)
        libm.so.6 => /usr/lib/libm.so.6 (0x00007f06cc6fa000)
        libc.so.6 => /usr/lib/libc.so.6 (0x00007f06cc400000)
        libz.so.1 => /usr/lib/libz.so.1 (0x00007f06ccbc8000)
        libbrotlienc.so.1 => /usr/lib/libbrotlienc.so.1 (0x00007f06cc314000)
        libbrotlidec.so.1 => /usr/lib/libbrotlidec.so.1 (0x00007f06cd2aa000)
        libzstd.so.1 => /usr/lib/libzstd.so.1 (0x00007f06cc1fa000)
        /lib64/ld-linux-x86-64.so.2 => /usr/lib64/ld-linux-x86-64.so.2 (0x00007f06cd412000)
        libgcc_s.so.1 => /usr/lib/libgcc_s.so.1 (0x00007f06ccb92000)
        libbrotlicommon.so.1 => /usr/lib/libbrotlicommon.so.1 (0x00007f06ccb6f000)
```
