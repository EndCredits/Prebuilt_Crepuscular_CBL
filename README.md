# Crepuscular Clang
-------
- Prebuilt clang binary files from CBL mainline.

- No need to set LD_LIBRARY_PATH

- binutils included

arch: X86_64, arm, arm64

LLVM toolchain ( Copyright (C) LLVM Project )

To download this clang, please run:

```
git clone https://gitlab.com/EndCredits/Prebuilt_Crepuscular_CBL.git <path to where you want to clone>
```

To use, either run:

```
export PATH=<path to your clone directory>/bin:${PATH}
```

or add:

```
PATH=<path to your clone directory>/bin:${PATH}
```

to the command you want to use this toolchain.


Version information:

Crepuscular clang version 14.0.0 (https://github.com/llvm/llvm-project c140ff493e84bbe697b78ac31fda427e4f8e12da)

Target: x86_64-unknown-linux-gnu

Thread model: posix

InstalledDir: /home/crepuscular/tc-build/install/bin

LLD 14.0.0 (compatible with GNU linkers)
