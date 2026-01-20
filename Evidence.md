### Examination Environment and Attached Storage

The forensic workstation was examined prior to acquisition to identify all connected storage devices. Dedicated drives were used for evidence storage and analysis to prevent cross-contamination and ensure forensic integrity.

![Forensic workstation environment showing attached storage devices](lab1-environment-and-attached-drives.png)

To independently validate file integrity, cryptographic hash values were generated using HashCalc. This step provided an additional verification method outside of FTK Imager and demonstrated consistency across forensic tools.

Both MD5 and SHA-1 hashes were calculated for the validation file and recorded to establish a baseline for integrity verification.

![HashCalc MD5 and SHA1 hash validation](Assets/screenshots/lab1-hash-validation-hashcalc-md5-sha1.png)
