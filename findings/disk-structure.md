# Disk Structure and Partition Analysis

## Disk Overview
- **Disk Size**: 32 GB
- **File Systems**: NTFS (main OS partition), FAT32 (other partitions)
- **Analysis Period**: 21/03/2025 – 23/03/2025

---

## Partition Map
The disk contained **eight partitions** with various purposes:

1. **Vol 1** – Unallocated (0–2047)
2. **Vol 4** – Windows Recovery Environment (2048–1023999)
3. **Vol 5** – EFI System Partition (1024000–1226751)
4. **Vol 6** – Microsoft Reserved Partition (1226752–1259519)
5. **Vol 7** – Basic Data Partition (1259520–62912511)
6. **Vol 8** – Unallocated (62912512–62914559)

> **Note**: Primary OS files were found in Volume 7, with unallocated space suggesting potential remnants of deleted or hidden content.

---

## File Type Distribution
Autopsy identified the following distribution of file types:

- **Documents**: 19,923 files (17.3%)
- **Executables**: 29,665 files (25.8%)
- **Images**: 14,049 files (12.2%)
- **Videos**: 71 files (0.1%)
- **Audio**: 229 files (0.2%)
- **Other**: 31,563 files (27.5%)
- **Unknown**: 15,952 files (13.9%)
- **Not Analyzed**: 3,451 files (3.0%)

---

## Time Zone Configuration
- **System Time Zone**: `Etc/GMT` (UTC +0:00)
- **Observation**: This is inconsistent with the user’s documented presence in Australia, possibly indicating manual reconfiguration or default setting during OS installation.

---

## Summary
The disk’s structure revealed a heavily used system with extensive user activity and unallocated space suitable for forensic recovery. File analysis suggests a broad range of data types, with a noteworthy number of executables and unknown files that may warrant further reverse engineering or malware analysis.
