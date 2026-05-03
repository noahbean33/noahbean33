# Hi, I'm Noah Bean

**Embedded Systems & Firmware Engineer | Low-Level Systems Specialist**

I bridge the gap between hardware and high-level software. My expertise lies in developing robust firmware, real-time operating systems, and building systems "from the silicon up." With experience at **Intel** and **Collins Aerospace**, I focus on writing highly optimized, thread-safe code for critical environments.

---

### Technical Toolbox

| Category | Technologies |
| :--- | :--- |
| **Languages** | C, C++, Python, x86 & ARM Assembly |
| **Embedded/RTOS** | FreeRTOS, STM32 (CMSIS/HAL), Bare-Metal, Embedded Linux |
| **Low-Level** | Intel VT-x (Hypervisors), Bootloaders, Kernel Development, DMA, JTAG |
| **Protocols** | UART, SPI, I2C, Modbus RTU, Ethernet (TCP/IP) |
| **Tools/Env** | CMake, GDB, Oscilloscopes, Logic Analyzers, Git, Linux |

---

### Highlighted Projects

Featured Projects
I specialize in "from-scratch" implementations, ranging from kernel-mode virtualization to high-performance firmware for resource-constrained microcontrollers.

Low-Level Systems & Virtualization
Type-1 Hypervisor
Technology: Windows Kernel-Mode, Intel VT-x (VMX), C.

Architected a hypervisor enabling live virtualization of x64 systems through precise VMCS management and custom VM exit handling for CPUID, MSR, and I/O operations.

Implemented Extended Page Tables (EPT) for second-level address translation, facilitating stealthy page-level monitoring ("hidden hooks") and system call interception.

Operating System Kernel
Technology: x86 Assembly, C, VFS.

Developed a multithreaded x86 kernel starting from a custom assembly bootloader that handles the transition from Real Mode to 32-bit Protected Mode.

Engineered a process management subsystem featuring a task scheduler, privilege separation (Ring 0/3), and an ELF binary loader.

Implemented a Virtual File System (VFS) with a FAT16 driver and low-level drivers for ATA disks and PS/2 keyboards.

C Compiler
Technology: C, x86 Assembly, Lexer/Parser.

Built a compiler from scratch with a custom lexical analyzer and parser to generate Abstract Syntax Trees (AST) for a subset of C, supporting pointers, structs, and multi-dimensional arrays.

Engineered a backend that translates ASTs into 32-bit Intel x86 assembly, maintaining binary compatibility with the GCC standard library.

Embedded & RTOS Development
Custom RTOS Kernel
Technology: ARM Assembly, STM32, C.

Architected an RTOS kernel from scratch, leveraging ARM assembly for low-level context switching within the PendSV handler.

Developed priority-based preemptive, round-robin, and time-triggered schedulers to ensure deterministic execution.

Implemented synchronization primitives including semaphores, mailboxes, and message queues alongside bare-metal drivers.

Production-Grade Air Quality Monitor
Technology: STM32F446RE, FreeRTOS, CMSIS, Modbus RTU.

Architected a multi-tasking firmware with five concurrent application tasks for sensor acquisition and system health monitoring.

Developed high-performance register-level drivers using CMSIS (bypassing HAL) to manage GPIO, UART, SPI, and I2C with DMA and interrupt-driven logic.

Integrated a custom Modbus RTU slave protocol for industrial monitoring using thread-safe synchronization primitives.

IoT Weather Station
Technology: ESP32 (ESP-IDF), AWS IoT Core, FreeRTOS.

Integrated AWS IoT Core via MQTT over TLS for secure real-time data publishing.

Optimized reliability via a dual-core task architecture, a custom state machine for WiFi management, and Over-the-Air (OTA) update capabilities.

---

### Professional Experience
* **Collins Aerospace:** Avionics firmware, automated hardware validation, and real-time DSP implementation.
* **Intel Corporation:** Post-silicon failure analysis and automation for server-grade silicon.

---

### Stats & Connect
[Website](https://noahbean33.github.io/) | [LinkedIn](https://www.linkedin.com/in/noah-bean-343612160) | [Medium](https://medium.com/@noahbean3396)

[![Noah's GitHub stats](https://github-readme-stats.vercel.app/api?username=noahbean33&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)