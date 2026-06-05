# Device Tree for Flower Plant S1 (flowS1) 🌸📱

This repository contains the official device tree configurations for the **Flower Plant S1** (Codename: `flowS1`), customized and optimized for **TwOS** (Linux-based Next-Gen Operating System).

---

## 🚀 Vision & Overview
The **Flower Plant S1** is a revolutionary open-source-focused flagship device designed to bridge the gap between absolute user freedom and cutting-edge hardware performance. Built with a 360-degree all-around screen layout and high-speed storage technology, it is optimized to run TwOS out of the box with 100% GSI (Generic System Image) compatibility.

> **Note:** This repository is built adhering to pure AOSP and Project Treble standards, ensuring future official lineageOS compatibility.

---

## 🛠️ Hardware Specifications (Target)

| Component | Specification |
| :--- | :--- |
| **CPU** | Flower Lotus 1000M (4.7-6.4 GHz OC RISC-V) |
| **GPU** | Petal-X GPU |
| **NPU** | Root-Ally NPU (250 TOPS) |
| **Memory & Storage** | 64 GB of FPRAM (Flower Permanent RAM) Technology |
| **Battery** | 7500 mAh with 120W Fast Charging & Ultra-thin Solar Panel |
| **OS** | TwOS Premium (TwOS Architecture) |

---

## 📂 Repository Structure
An organized layout of the device tree components:
* `configs/` - Custom hardware, audio, and media configurations.
* `overlay/` - System UI and framework modifications specific to the all-around screens.
* `rootdir/` - Init scripts and kernel parameters (`init.target.rc`).
* `AndroidProducts.mk` - Lunch choices and product definitions.
* `BoardConfig.mk` - Target architecture definitions (RISC-V) and partition layout.

---

## 🏗️ How to Build TwOS for flowS1

### 1. Initialize the Source Tree
To initialize your local repository container, run:
```bash
repo init -u [https://github.com/FlowerTechnologies-dev/twos_manifest.git](https://github.com/FlowerTechnologies-dev/twos_manifest.git) -b twos-16.0
