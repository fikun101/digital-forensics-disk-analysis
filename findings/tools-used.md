# Tools Used in Digital Forensics Analysis

## 1. **Autopsy**
Autopsy was the primary tool used for disk image analysis. It provided:
- File recovery (including deleted files)
- Keyword search
- Timeline reconstruction
- Extraction of browser history, cached data, and system artifacts

## 2. **Case Note**
Used to securely record contemporaneous notes, timestamps, and observations during the investigation. Ensures transparency and proper documentation in accordance with legal standards.

## 3. **Hash Verification Tools**
To verify integrity before and after analysis:
- **MD5** and **SHA-256** cryptographic hash functions
- Confirmed that no alteration occurred to disk images during investigation

## 4. **Steganography Analysis Tools**
Employed to scan image files for hidden content or encrypted data:
- Detected signs of covert communication or data concealment

## 5. **Write-Blocking Tools/Techniques**
Used to prevent modification of original evidence:
- Ensured analysis occurred on forensic duplicates only
- Maintained legal admissibility of findings

## 6. **Filesystem Analysis Utilities**
Within Autopsy and system logs:
- Examined NTFS and FAT32 partitions
- Recovered deleted images and files from unallocated space

## 7. **Windows System Logs & Registry Artifacts**
Used to extract:
- Installed program history (e.g., TrueCrypt, CCleaner)
- USB device connections
- System timezone and OS metadata

---

These tools combined ensured a thorough, reliable, and court-admissible digital forensics process.
