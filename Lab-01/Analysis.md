## File System Identification and Initial Examination

Initial analysis was conducted using **FTK Imager** to identify the file system structure of the attached USB device and confirm media integrity prior to deeper examination. The evidence volume was identified as **FAT32**, and the boot sector was reviewed in both logical and hexadecimal views to validate structural consistency and file system signatures.

This step established baseline confidence in the media format and ensured the device could be analyzed safely without introducing modification or corruption.

![FAT32 file system identification in FTK Imager](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-01/Assets/screenshots/lab1-fat32-file-system-identification-ftk.png)

---

Following FAT32 identification, a second attached storage device was examined to determine its file system type and metadata structure. FTK Imager identified this volume as **NTFS**, and the boot sector was reviewed in hexadecimal view to confirm file system signatures and core metadata.

Validating the NTFS structure ensured proper handling of the volume and established readiness for any subsequent file-level or artifact-based analysis.

![NTFS file system identification in FTK Imager](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-01/Assets/screenshots/lab1-ntfs-file-system-identification-ftk.png)
