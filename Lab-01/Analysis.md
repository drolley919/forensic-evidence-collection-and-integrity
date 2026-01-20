## File System Identification and Initial Examination

The USB device was examined using FTK Imager to identify the underlying file system and validate structural integrity prior to deeper analysis. The evidence was recognized as a FAT32-formatted volume, and the boot sector was reviewed in both logical and hex views.

This step confirmed the file system type and ensured the media could be safely analyzed without modification.

![forensic-evidence-collection-and-integrity](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-01/Assets/screenshots/lab1-fat32-file-system-identification-ftk.png)

Following identification of the FAT32 volume, the second attached storage device was examined to determine its file system structure. FTK Imager identified the volume as NTFS, and the boot sector was reviewed in hex view to validate the file system signature and metadata.

This step confirmed the presence of an NTFS-formatted volume and ensured proper handling prior to any file-level or artifact analysis.

![FTK Imager NTFS file system identification](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-01/Assets/screenshots/lab1-ntfs-file-system-identification-ftk.png)
