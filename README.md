Modified source code to use `e4defrag` on android (termux) and add this README.md.

compile:

```
sudo apt install gcc-9-aarch64-linux-gnu texinfo
git clone ...
cd e2fsprogs
mkdir build
cd build
../configure --host=aarch64-linux-gnu CC=aarch64-linux-gnu-gcc-9 LD=aarch64-linux-gnu-ld LDFLAGS=--static
make
scp misc/e4defrag ...
```

