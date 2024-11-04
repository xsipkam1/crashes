# AFL CRASHES

Otestované na WSL.

Treba skompilovať `main.c` takto: **`afl-gcc -o -g main main.c`**

Spustiť program sa môže napr. takto: **`./main buffer_overflow_79`**

Pre ladenie cez gdb: **`gdb --args ./main buffer_overflow_79`**


# AFL CRASHES

Tested on WSL.

To compile `main.c`, use the following command: **`afl-gcc -o -g main main.c`**

To run the program, you can use a command like this: **`./main buffer_overflow_79`**

For debugging with gdb, use: **`gdb --args ./main buffer_overflow_79`**
