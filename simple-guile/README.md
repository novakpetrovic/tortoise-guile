Sample code from [Section 2.3 (Linking Guile into Programs) of the Guile 2.0 Reference Manual](https://www.gnu.org/software/guile/docs/docs-2.0/guile-ref/Linking-Guile-into-Programs.html), compiled on Cygwin with:
```
gcc -o simple-guile.exe simple-guile.c `pkg-config --cflags --libs guile-2.0`
```

Results that I get:

![screenshot-0](/simple-guile/screenshot-0.png)

![screenshot-1](/simple-guile/screenshot-1.png)





