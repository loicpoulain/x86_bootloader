x86_bootloader
==============

simple X86 asm bootloader

This is a basic x86 bootloader
- Load 'kernel' from 2nd sector
- Load Global Descriptor Table
- Switch to protected mode
- Execute kernel

run (qemu):
qemu-system-i386 -fda boot.flp

contact: loic.poulain@gmail.com
