## Forensic Image Integrity Verification

### Folder-Level Image Verification
A forensic image of a document folder was acquired using **FTK Imager** and immediately verified to confirm evidentiary integrity. Cryptographic hash values were automatically generated during the acquisition and verification process.

Both **MD5** and **SHA-1** hash values matched successfully, confirming that the folder image was acquired without modification and remained unchanged during validation.

![FTK Imager folder image hash verification results](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-02/Assets/screenshots/lab2-folder-image-hash-verification-ftk.png)

---

### NTFS Drive Image Verification
A full **NTFS-formatted drive image** was acquired and verified using FTK Imager to ensure forensic completeness and integrity. The verification process compared calculated and reported cryptographic hash values.

Both MD5 and SHA-1 hashes matched, and no bad sectors were identified during imaging. These results confirm that the drive image was acquired accurately and remained unaltered throughout the verification process.

![FTK Imager NTFS drive image hash verification results](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-02/Assets/screenshots/lab2-ntfs-drive-image-hash-verification-ftk.png)

---

### FAT32 Drive Image Verification
A **FAT32-formatted drive image** was also acquired and verified as part of the examination. Cryptographic hash values were generated and compared to validate image integrity.

Both MD5 and SHA-1 hash values matched successfully, and no acquisition errors were reported. This confirms that the FAT32 image was preserved without alteration during acquisition and verification.

![FTK Imager FAT32 drive image hash verification results](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-02/Assets/screenshots/lab2-fat32-drive-image-hash-verification-ftk.png)

---

## Independent Hash Validation (Cross-Tool Verification)

### AD1 Evidence File Validation
To reduce reliance on a single forensic tool, the acquired **AD1 evidence file** (`Document Folder.ad1`) was independently validated using **HashCalc**. Hash values were generated outside of FTK Imager and compared against the original acquisition values.

Both MD5 and SHA-1 hash values matched, confirming consistency across forensic tools and reinforcing confidence in evidence integrity.

![HashCalc verification of AD1 document folder image](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-02/Assets/screenshots/lab2-hashcalc-ad1-document-folder-hash-verification.png)

---

### NTFS Disk Image Cross-Verification
The NTFS disk image (`NTFS Drive.001`) was independently validated using HashCalc to confirm integrity beyond the acquisition tool.

Both MD5 and SHA-1 hash values matched the original acquisition results, confirming that the disk image remained unchanged and forensically sound.

![HashCalc verification of NTFS disk image](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-02/Assets/screenshots/lab2-hashcalc-ntfs-drive-001-hash-verification.png)

---

### FAT32 Disk Image Cross-Verification
The FAT32 disk image (`FAT32 Drive.001`) was also independently validated using HashCalc to confirm cross-tool consistency.

Matching MD5 and SHA-1 hash values verified that the FAT32 image remained unaltered throughout the examination process.

![HashCalc verification of FAT32 disk image](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-02/Assets/screenshots/lab2-hashcalc-fat32-drive-001-hash-verification.png)

---

## Artifact-Level Integrity Validation

### Hash List File Verification
To ensure integrity of analysis outputs, the generated hash list file (`Documents Image Hash List.csv`) was independently validated using HashCalc. This step confirmed that analytical artifacts themselves were not altered after creation.

MD5 and SHA-1 hash values were successfully generated and recorded, supporting the reliability and auditability of reported results.

![HashCalc verification of documents image hash list](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-02/Assets/screenshots/lab2-hashcalc-documents-image-hash-list-csv-verification.png)

---

### Hash List Review and Validation
The generated hash list file was reviewed using **OpenOffice Calc** to confirm completeness, readability, and traceability of recorded hash values.

The file contained corresponding filenames alongside MD5 and SHA-1 hash values, supporting accurate documentation and verification throughout the forensic examination.

![Documents image hash list reviewed in OpenOffice Calc](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-02/Assets/screenshots/lab2-documents-image-hash-list-openoffice-review.png)
