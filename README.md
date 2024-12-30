# Toolchain components for Picolibc CI

| File             | Source | Build script |
| ---------------- | ------ | ------------ |
| m68k-unknown-elf.tar.xz      | https://github.com/keith-packard/gcc/tree/m68k-soft-float | my-gcc-m68k-configure |
|                  | https://github.com/bminor/binutils-gdb/tree/binutils-2_43_1 | my-binutils-m68k-configure |
| msp430-unknown-elf.tar.xz | https://github.com/crosstool-ng/crosstool-ng/tree/crosstool-ng-1.25.0 | |
| qemu-arc.tar.xz  | https://github.com/keith-packard/qemu-arc/tree/frnd-ties-away | my-qemu-arc-configure |
| qemu-m68k.tar.xz | https://github.com/keith-packard/qemu/tree/m68k-semihosting | my-qemu-m68k-configure |
| qemu-nios2.tar.xz | https://github.com/keith-packard/qemu/tree/nios2-semi-lseek | my-qemu-nios2-configure |
| sh-unknown-elf.tar.xz	   | https://github.com/crosstool-ng/crosstool-ng/tree/crosstool-ng-1.25.0 | |
