<div align="center">

# 🛑 **CRITICAL WARNING** 🛑

### **DO NOT UNZIP THIS FILE ON YOUR LOCAL MACHINE**

[![Danger](https://img.shields.io/badge/DANGER-EXTREME-red?style=for-the-badge&logo=hack-the-box)](https://en.wikipedia.org/wiki/Zip_bomb)
[![Size](https://img.shields.io/badge/UNCOMPRESSED%20SIZE-in%20PETABYTES-black?style=for-the-badge&labelColor=red)](https://en.wikipedia.org/wiki/Petabyte)
[![Malware Classification](https://img.shields.io/badge/TYPE-DECOMPRESSION%20BOMB-yellow?style=for-the-badge&logo=warning)](https://en.wikipedia.org/wiki/Zip_bomb)

<br />

<h1>☠️ <br>THIS IS A ZIP BOMB</h1>

<p>
<b>This repository contains a recursive archive designed for security research and testing system resilience. <br>
Attempting to decompress this file will result in catastrophic resource exhaustion.</b>
</p>

</div>

---

## ⚡ What is inside?

This file utilizes a recursive compression algorithm. While the file size on disk appears negligible (kilobytes or megabytes), the uncompressed data structure expands exponentially.

| Metric | Value |
| :--- | :--- |
| **Download Size** | ~40MB |
| **Depth** | Recursive Layers |
| **Uncompressed Size** | **~ FEW PETABYTES** |
| **Potential Impact** | System Freeze / Crash |

> **definition:** A *zip bomb*, also known as a decompression bomb or zip of death, is a malicious archive file designed to crash or render useless the program or system reading it.

---

## ⚠️ The Consequences

If you attempt to extract this archive on a standard personal computer, the following will occur immediately:

1.  **RAM Exhaustion:** Your available memory will fill instantly as the extraction tool attempts to map the file structure.
2.  **Disk I/O Lock:** Your hard drive read/write operations will hit 100%, causing the OS to freeze.
3.  **Storage Overflow:** If the process continues, it will attempt to write petabytes of data to a drive that likely only has terabytes of space.
4.  **Hard Reset Required:** You will likely be forced to physically power cycle your machine.

---

## 🧪 Safe Usage Protocol

**ONLY** interact with this file if you are a security researcher or system administrator testing:
* Antivirus scanning engines.
* Server upload limiters.
* Sandboxed environments.

### Recommended Environment:
* [x] **Isolated Virtual Machine (VM)**
* [x] **No Network Connection**
* [x] **Dedicated Storage Partition**

```bash
# DO NOT RUN THIS COMMAND
unzip data.zip
