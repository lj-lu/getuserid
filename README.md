**INSTALLATION**

This document accounts for installing BlackArch Linux, a distribution of Arch Linux with a focus on penetration testing. It explains downloading the ISO, creating a bootable USB, and using
the integrated installer to install the system. The key points are partitioning setup, selecting a desktop environment, and creating a user. It is intended to establish a
lightweight but robust system optimized for security research. It's
an economical way of gaining access to advanced tools in a Linux environment.

**SYSTEM CALL IMPLEMENTATION**:**getuserid()**

The system call employed here within this project is getuserid(), which provides the
user ID of the calling process (UID). It's planted directly into Linux
kernel codebase and exported as syscall tables. Upon calling, it provides the UID
as integer value similar to getuid() internally. It demonstrates how kernel extensions
at a low level are written and provides a foundation upon which to install custom
OS-level functionality. It's a nice but simple example of making system calls in
Linux.
