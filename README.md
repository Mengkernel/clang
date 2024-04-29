# Cirrus CI Build Status
[![Build Status](https://api.cirrus-ci.com/github/Diaz1401/clang-build.svg?branch=main)](https://cirrus-ci.com/Diaz1401/clang-build)

# Download
Check latest release [here](https://github.com/Mengkernel/clang/releases/latest)

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
  ==> Minimal LLVM 19.0.0git-20240429 targeting 'AArch64' and 'X86'
  ==> Stripped binaries
  ==> Download size 220MB
  ==> Compressed tar archive with zstd v1.5.5
  ==> Build LLVM Polly & LLD
  ==> Build with ThinLTO + PGO
```
# Build script

  Visit https://github.com/Diaz1401/clang-build
