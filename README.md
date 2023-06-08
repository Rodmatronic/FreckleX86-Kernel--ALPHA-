# FreckleX86-Kernel--ALPHA-
A very small kernel, that makes a Window, and a menu bar, that's it!
HOW TO RUN:
If you download the binary, this is what to run:
You need QEMU to run this kernel, Run:

wget https://download.qemu.org/qemu-8.0.2.tar.xz
tar xvJf qemu-8.0.2.tar.xz
cd qemu-8.0.2
./configure
make

Now, run:

qemu-system-i386 -kernel kernel
in the directory that contains the "kernel" file.
Bam!
