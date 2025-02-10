`system/etc/init.d/01mod`

```sh
#!/system/bin/sh
#
# Mod by akku
#
L="log -p i -t akkumod"

$L "Fixing permissin"
$L "/dev/ion"
chmod 0666 /dev/ion
```

replace `lib/libm4u.so` with 4.4
