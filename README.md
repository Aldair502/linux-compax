<div align="center">
  <br/>
  <h1 align="center">Linux-Compax</h1>
  <p align="center">Just some mess of patches and settings to squeez every bit of performance.</p>
</div>


- [General Information about the kernel](#general-information-about-the-kernel)
  - [Features](#features)
  - [Contributors](#contributors)
  - [Flags](#flags)

# General Information the about kernel
A specific PKGBUILD made for the Compax Green Air and W9x0LU motherboards.

## Features
The same as [Cachyos](https://github.com/CachyOS/linux-cachyos#features) but with a optimized kernel for x86_64 from nitrous, intel clear patches and built with flutex and winesync in it
Also already made configs for the Intel(R) Celeron(R) CPU  N3060

## Contributors
[Hamad Marri](https://github.com/hamadmarri) for the TT Scheduler <br />
[Archlinux](https://archlinux.org) for the great linux operating system <br />
[Linux-Nitrous](https://github.com/xdevs23/linux-nitrous) for a great kernel fork <br />
[Cachyos](https://github.com/CachyOS/linux-cachyos) for a great PKGBUILD <br />
[Xanmod](https://github.com/xanmod/linux-patches) for wine and flutex patches <br />
[ClearLinux](https://github.com/clearlinux-pkgs/linux) for intel specific patches <br />
[And all other Kernel Developers and Supporters](https://github.com/torvalds/linux) <br />

## Flags
-march=silvermont -mtune=native -maes --param=l1-cache-line-size=64 --param=l1-cache-size=24 --param=l2-cache-size=1024 -Ofast -mfpmath=sse -mstackrealign -ftree-vectorize -funroll-loops -fno-defer-pop -ffast-math -mfma -mprefetchwt1 -mpclmul -mpopcnt -mprefetchwt1 -fprefetch-loop-arrays -msse4.2 -mno-avx -mno-avx2
