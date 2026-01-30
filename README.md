Perfect — here’s a polished, English-language `README.md` for your project **SpectrOS 1 Mini**, reflecting that it was written in Catalan, uses the **GPL v3 license**, and includes compatibility and technical details suited for GitHub.  

---  

# 💡 SpectrOS 1 Mini

**SpectrOS 1 Mini** is a **lightweight experimental operating system**, entirely written in **Catalan**, developed from the ground up in **Assembly (NASM)**.  
It’s designed for learning, experimentation, and demonstrating the core mechanisms that make computers and kernels work.

***

## 🌍 About the Project

SpectrOS 1 Mini aims to provide a simple yet functional environment for developers and students who want to explore **low-level system architecture**.  
This version focuses on **stability, simplicity, and clarity of design**, making it ideal for use in virtual machines or real x86 hardware.

***

## ⚙️ Core Features

- Real **bootloader and kernel** written from scratch in C and NASM  
- Basic **memory handling** and **interrupt management**  
- **Keyboard (PS/2)** input support  
- **VGA text and graphical modes**  
- Simple **shell-like interface** for interaction  
- Compact ISO/IMG for quick booting  
- Fully **documented in Catalan**

***

## 🖥️ Compatibility

SpectrOS 1 Mini supports both virtualized and physical hardware environments:

- ✅ **QEMU** (recommended for testing)  
- ✅ **VirtualBox**  
- ✅ **Bochs**  
- ⚙️ **Real Machines (x86 32-bit)** — bootable via USB or CD  
- 💽 Format: `.img` (bootable floppy/drive image)

Minimum requirements:

- CPU: Intel/AMD/ARM x86 32-bit  
- RAM: 32 MB minimum (64 MB recommended)  
- Disk: 10 MB free space  

***

## 🧰 Build & Run

If you’d like to rebuild or modify the system:

1. Install dependencies:
   ```bash
   sudo apt update
   sudo apt install qemu-system-x86
   ```

2. Clone the repository:
   ```bash
   git clone https://github.com/yourname/spectros1mini.git
   cd spectros1mini
   ```
 
If you just want to test the existing `.img` file:
   ```bash
   qemu-system-x86_64 -fda spectros.img
   ```

***

***

## 🧑‍💻 Contribution

Contributions are appreciated!  
You can help by improving code, documentation, or translations.

- Report bugs or open discussions on GitHub Issues  
- Fork, modify, and submit pull requests  
- Translate documentation or kernel messages (Catalan is the main language)

Please ensure the system still builds (`make all`) before submitting changes.

***

## 📜 License

SpectrOS 1 Mini is released under the **GNU General Public License v3.0 (GPLv3)**.  
You are free to use, modify, and distribute the project under the same terms.  
See the `LICENSE` file for details.

***

## 🇨🇦 Written in Catalan

This entire system — code comments, documentation, and shell messages —  
has been proudly **written in the Catalan language** 🇪🇸.  
It showcases that **Catalan can be a language for technology, programming, and systems development**.

***

## 🧠 Purpose

SpectrOS 1 Mini serves as both a **learning tool and a technical demo**,  
highlighting how an operating system boots, manages control flow, and interacts with hardware — all through clean, handcrafted low-level code.

***
