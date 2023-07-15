Compiler Bahasa Jawa
=====================

Merupakan kompiler bahasa pemrograman Jowo (bukan Java). Ini merupakan riset dari mas Robin buat mempelajari LLVM.

Kompiler ini asli bukan parodi dan bisa menghasilkan native binary untuk multi platform Linux, OSX, Windows, dan binary untuk ARM dan MIPS.


Contoh algoritma Fibonacci dalam bahasa Jowo:

```
fungsi fib(double n):double
mulai
    nek n < 2.0 njuk
        nyoh n
    nek ora
        nyoh fib(n - 1.0) + fib(n - 2.0)
bar
```

Contoh lainnya bisa dilihat di `examples/`.

Cara kompile:

    $ ./bosojowoc examples/fibbo.jowo


Walaupun ini kompiler asli, namun masih sangat dasar, masih banyak fungsi kompiler yang belum diimplementasikan.
