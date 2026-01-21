## Evidence Integrity and Storage Validation

### Forensic Image Integrity Verification
The acquired forensic image was verified using **FTK Imager** to confirm data integrity following acquisition. Cryptographic hash values were generated and compared during verification.

Both **MD5** and **SHA-1** hash values matched successfully, confirming that the image remained unchanged. No bad sectors or integrity issues were detected, supporting the reliability of the acquired evidence.

![FTK Imager image verification results](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-03/Assets/screenshots/lab3-ftk-image-verification.png)

---

### Attached Storage Identification
Prior to forensic imaging, **Windows Disk Management** was used to identify all attached storage devices and review file systems and partition layouts. This step established awareness of connected **FAT32 and NTFS volumes** and supported proper evidence handling and segregation.

Documenting attached storage reduced the risk of cross-contamination and ensured that only intended media were involved in acquisition activities.

![Disk Management showing attached storage devices](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-03/Assets/screenshots/lab3-disk-management-attached-volumes.png)

---

### Forensic Storage Disk Validation
Disk Management was used to identify and validate the disk designated for forensic evidence storage. The forensic volume was confirmed as a healthy **NTFS-formatted primary partition** prior to imaging activities.

This validation ensured that evidence was written only to approved storage media and supported forensic integrity throughout the examination.

![Disk Management highlighting forensic storage disk](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-03/Assets/screenshots/lab3-disk-management-forensic-storage-disk.png)

---

### Unallocated Space Verification
The forensic storage disk was further examined to document the presence of unallocated space. Disk Management confirmed that no additional partitions or hidden volumes were present prior to evidence acquisition.

Recording unallocated space supports transparency and helps ensure that no undocumented storage areas existed that could affect evidence handling or interpretation.

![Disk Management showing forensic disk and unallocated space](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-03/Assets/screenshots/lab3-disk-management-forensic-disk-unallocated.png)
