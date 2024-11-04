# AFL CRASHES

Otestované na WSL.
Treba skompilovať main.c takto: afl-gcc -o -g main main.c

Spustiť program sa môže napr. takto: ./main buffer_overflow_79
Pre ladenie cez gdb: gdb --args ./main buffer_overflow_79
