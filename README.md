## Introduction

This project is part of my second semester coursework, where I am building a simple hardware interface using **QEMU** on **Ubuntu**. I use QEMU as an emulator to run and test a minimal operating system that I compiled myself, without relying on physical hardware.

The main goals of this project are:
- Simulate the boot process of a custom-compiled Linux kernel
- Create a basic operating system structure with directories and user management
- Explore how virtual devices, file systems, and terminal interfaces interact
- Learn the fundamentals of how an operating system works at a low level

QEMU helps me achieve this by allowing:
- Full x86 system emulation
- Creation of a bootable `.iso` image
- Integration with BusyBox, GRUB, and an initrd for a lightweight runtime
- Safe and repeatable testing in a virtual environment

All development is done on Ubuntu, using tools such as `make`, `grub`, `busybox`, `openssl`, and `qemu-system-x86_64`. This project has been both a challenge and a valuable learning experience in understanding low-level system operations.

---
