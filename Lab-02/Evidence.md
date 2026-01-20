## Folder Image Integrity Verification

A forensic image of a folder was created and verified using FTK Imager to confirm evidentiary integrity. Cryptographic hash values were automatically generated and compared during the verification process.

Both MD5 and SHA-1 hash values matched the reported values, confirming that the image was not altered during acquisition or validation.

![FTK Imager folder image hash verification results]

## NTFS Drive Image Integrity Verification

A full NTFS drive image was acquired and verified using FTK Imager to ensure forensic integrity and completeness. The verification process compared computed and reported cryptographic hash values.

Both MD5 and SHA-1 hashes matched successfully, and no bad sectors were identified during imaging. This confirms that the drive image was acquired without error and remained unaltered during verification.

![FTK Imager NTFS drive image hash verification results]

## FAT32 Drive Image Integrity Verification

A FAT32-formatted drive image was also acquired and verified using FTK Imager as part of the forensic examination. Cryptographic hash values were calculated and compared to confirm image integrity.

Both MD5 and SHA-1 hash values matched successfully, and no bad sectors were identified during the verification process. This confirms that the FAT32 drive image was acquired accurately and preserved without alteration.

![FTK Imager FAT32 drive image hash verification results]

## Independent Hash Verification of AD1 Evidence File

To further validate forensic integrity, the acquired AD1 evidence file was independently verified using HashCalc. Cryptographic hash values were generated outside of FTK Imager to confirm consistency across forensic tools.

Both MD5 and SHA-1 hash values were successfully calculated for the `Document Folder.ad1` evidence file, supporting the integrity and authenticity of the acquired data.

![HashCalc verification of AD1 document folder image]

## Independent Hash Verification of NTFS Disk Image

To ensure forensic integrity beyond the acquisition tool, the NTFS disk image (`NTFS Drive.001`) was independently validated using HashCalc. Cryptographic hash values were generated and compared to confirm consistency with the original acquisition results.

Both MD5 and SHA-1 hashes matched the values reported during image creation, confirming that the disk image remained unchanged and forensically sound.

![HashCalc verification of NTFS disk image]

## Independent Hash Verification of FAT32 Disk Image

To further validate forensic integrity, the FAT32 disk image (`FAT32 Drive.001`) was independently verified using HashCalc. Cryptographic hash values were generated outside of FTK Imager to confirm consistency across forensic tools.

Both MD5 and SHA-1 hashes matched the values recorded during acquisition, confirming that the FAT32 disk image remained unchanged and forensically sound throughout the examination process.

![HashCalc verification of FAT32 disk image]

## Artifact-Level Hash Verification of Generated Hash List

To ensure artifact-level integrity, the hash list file generated during the examination (`Documents Image Hash List.csv`) was independently validated using HashCalc. This step confirmed that analysis outputs themselves were not altered after creation.

MD5 and SHA-1 hash values were successfully generated and recorded, providing assurance that the hash list remained unchanged and reliable for verification and reporting purposes.

![HashCalc verification of documents image hash list]

## Review of Generated Hash List for Document Image

The generated hash list file (`Documents Image Hash List.csv`) was opened and reviewed using OpenOffice Calc to verify the completeness and readability of recorded hash values. The file contains MD5 and SHA-1 hash values alongside corresponding filenames extracted from the document image.

This review step ensured that all examined files were properly cataloged with their associated cryptographic hashes, supporting traceability, integrity verification, and reporting accuracy throughout the forensic examination.

![Documents image hash list reviewed in OpenOffice Calc]
