# Hardware Devices and External Volumes

## Overview
System logs revealed multiple hardware devices connected to the system during its active period. These included USB storage devices, virtual interfaces, and root hubs.

---

## Key Devices Identified

### 1. **Seagate Backup Plus Slim Portable Drive**
- **Capacity**: 1TB
- **Device ID**: MSFT30NA9LP8HF
- **Connection Date**: 31/01/2019
- **Forensic Concern**: High likelihood of sensitive file transfers to or from the device

### 2. **VMware Virtual USB Hub**
- Detected in system logs
- Indicates use of a **virtualized environment** for isolated operations

### 3. **Multiple USB Root Hubs (2.0 & 3.0)**
- Connected on 02/02/2019
- Suggests active USB activity during the period of interest

---

## Forensic Implications
- The Seagate external drive may hold additional evidence or backups that were not captured in the disk image.
- USB activity suggests potential file exfiltration or external manipulation of data.
- The presence of VMware components reinforces the possibility that the user intended to compartmentalize sensitive operations or avoid detection.

---

## Conclusion
The presence of USB storage and virtual hubs adds important context to the investigation. Further action should include locating and imaging the Seagate drive (if available), as well as deeper inspection of logs related to device connection times and file transfers.
