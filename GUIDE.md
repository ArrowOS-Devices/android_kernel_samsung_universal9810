# Arch Linux

## Links

<http://events17.linuxfoundation.org/sites/events/files/slides/Shuah_Khan_cross_compile_linux.pdf>

## Packages

```bash
# pacman -S aarch64-linux-gnu-gcc
```

## Compile

```bash
make mrpropper
make ARCH=arm64 exynos9810-starlte_defconfig
CC=clang ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- CLANG_TRIPLE=aarch64-linux-gnu- make
```
