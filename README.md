# SimpleRealModeBootLoader

Welcome to SimpleRealModeBootLoader! This repository contains a basic 16-bit real mode bootloader written in Assembly language. It is designed for educational purposes to help you understand the core concepts of bootloaders, system programming, and the early stages of the boot process in x86 architecture.

## Features
- Minimalistic bootloader that fits within the first 512 bytes of the boot sector
- Demonstrates the basics of real mode operation
- Provides a clear and well-commented Assembly source code for easy understanding
- Loads and executes a simple "Hello World" kernel

## Getting Started

### Prerequisites
- **NASM**: An assembler for the x86 architecture
- **QEMU**: A generic and open source machine emulator and virtualizer
- **dd**: A command-line utility for Unix and Unix-like operating systems

### Installation

1. **Clone the repository:**
   ```bash
   https://github.com/harshithsunku/SimpleRealModeBootLoader.git
   cd SimpleRealModeBootLoader
   
2. **Assemble the bootloader:**
   ```bash
   nasm -f bin bootloader.asm -o bootloader.bin

3. **Run the bootloader using QEMU:**
   ```bash
   qemu-system-x86_64 -hda ./boot.bin

## License

This project is licensed under the [GNU General Public License v3 (GPLv3)](LICENSE).![image](https://github.com/user-attachments/assets/9917a3da-af3d-4f28-84c8-83246f5587d9)





