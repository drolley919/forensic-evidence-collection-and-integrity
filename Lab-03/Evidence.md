### FTK Imager – Image Integrity Verification

The acquired forensic image was verified using FTK Imager to ensure data integrity following acquisition. Both MD5 and SHA-1 hash values matched the reported values, confirming the image remained unchanged. No bad sectors or corruption were detected during verification.

![FTK Imager image verification results](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-03/Assets/screenshots/lab3-ftk-image-verification.png)

### Disk Management – Attached Storage Identification

Prior to forensic imaging, Windows Disk Management was used to identify all attached storage devices and confirm their file systems and partition layouts. This step ensured awareness of connected FAT32 and NTFS volumes and supported proper evidence handling and segregation during acquisition.

![Disk Management showing attached storage devices](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-03/Assets/screenshots/lab3-disk-management-attached-volumes.png)

### Forensic Storage Disk Identification

Disk Management was further used to identify the specific disk designated for forensic evidence storage. The NTFS-formatted forensic volume was confirmed as a healthy primary partition prior to imaging activities to ensure proper evidence segregation and integrity.

![Disk Management highlighting forensic storage disk](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-03/Assets/screenshots/lab3-disk-management-forensic-storage-disk.png)

### Forensic Storage Disk and Unallocated Space Verification

Disk Management was used to confirm the forensic storage disk prior to imaging. The forensic volume was verified as an NTFS-formatted, healthy primary partition. Remaining unallocated space on the disk was documented to ensure no additional partitions or hidden data areas were present before evidence acquisition.

![Disk Management showing forensic disk and unallocated space](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-03/Assets/screenshots/lab3-disk-management-forensic-disk-unallocated.png)
