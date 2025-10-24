# tiny-os

This is my attempt of understanding low level programming a bit more. Built following this [tutorial](https://operating-system-in-1000-lines.vercel.app/en/04-boot).

## Source code structure

├── disk/ - File system contents
├── common.c - Kernel/user common library: printf, memset, ...
├── common.h - Kernel/user common library: definitions of structs and constants
├── kernel.c - Kernel: process management, system calls, device drivers, file system
├── kernel.h - Kernel: definitions of structs and constants
├── kernel.ld - Kernel: linker script (memory layout definition)
├── shell.c - Command-line shell
├── user.c - User library: functions for system calls
├── user.h - User library: definitions of structs and constants
├── user.ld - User: linker script (memory layout definition)
└── run.sh - Build script
