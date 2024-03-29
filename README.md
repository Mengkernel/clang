# GitHub Action Build Status
[![CI](https://github.com/Diaz1401/clang-build/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/Diaz1401/clang-build/actions/workflows/build.yml)

# Download
Check latest release [here](https://github.com/Diaz1401/clang/releases/latest)

# Simple installation method
```bash
rm -rf ~/.kucing-clang
mkdir ~/.kucing-clang
tar xf clang.tar.zst -C ~/.kucing-clang
if [ $USER == root ]; then
  echo 'export PATH=/root/.kucing-clang/bin:$PATH' >> ~/.bashrc
else
  echo 'export PATH=/home/$USER/.kucing-clang/bin:$PATH' >> ~/.bashrc
fi
source ~/.bashrc
clang --version
```

# Features
```
  ==> Minimal LLVM 19.0.0git-20240325 targeting 'AArch64' and 'X86'
  ==> Stripped binaries
  ==> Download size 358MB
  ==> Compressed tar archive with zstd v1.5.5
  ==> Build LLVM Polly & LLD
  ==> Build with ThinLTO + PGO
```
# Build script

  Visit https://github.com/Diaz1401/clang-build
