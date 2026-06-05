# Device Tree for Flower Plant S1 (flowS1) 🌸📱

This repository contains the official hardware configuration and device tree definitions for the **Flower Plant S1** (Codename: `flowS1`), specifically tailored for **TwOS** (Linux-based Next-Gen Operating System).

---

### 🚀 Vision & Overview
The **Flower Plant S1** is a revolutionary open-source flagship device designed to bridge the gap between absolute user freedom and cutting-edge hardware performance. Built with a 360-degree all-around screen layout and high-speed storage technology, it is optimized to run TwOS out of the box with advanced Linux-level optimization.

While TwOS runs on a native Linux foundation, this repository maintains 100% GSI (Generic System Image) core compliance at the hardware-vendor level, ensuring future alternative OS and custom ROM compatibility.

---

### 🛠️ Hardware Specifications (Target)

| Component | Specification |
| :--- | :--- |
| **CPU** | Flower Lotus 1000M (4.7-6.4 GHz OC RISC-V) |
| **GPU** | Petal-X GPU |
| **NPU** | Root-Ally NPU (250 TOPS) |
| **Memory & Storage** | 64 GB with FPRAM (Flower Permanent RAM) Technology |
| **Battery** | 7500 mAh with 120W Fast Charging & Ultra-thin Solar Panel |
| **OS** | TwOS (Linux-based Architecture) |

---

### 📂 Repository Structure
An organized layout of the TwOS native device components:
* `kernel/` - Custom Linux kernel configurations and drivers for RISC-V / Lotus 1000M.
* `hardware/` - HAL (Hardware Abstraction Layer) definitions for Petal-X GPU and solar panels.
* `configs/` - Display routing, audio policies, and custom framework configurations.
* `overlay/` - System-level tweaks specific to the 360-degree all-around screen form factor.

---

### 🏗️ How to Build TwOS for flowS1

> ⚠️ **Notice:** The proprietary TwOS native compilation toolchain and automated build scripts are currently under active internal development. 
>
> **TwOS Build System Instructions Will Be Added Soon.**

---

### 👥 Contributors & Maintainers

* **Lead Developer / Architect:** [Azeno42 (Muratcan Yücepur)](https://github.com/Azeno42)  
* **Organization:** [Flower Technologies](https://github.com/FlowerTechnologies-dev)

---

### 📄 Copyright & Licensing
All architecture code within this repository is property of **Flower Technologies**. Private commercial modifications for retail devices remain proprietary, while core hardware interface configurations adhere to open-source compliance.
