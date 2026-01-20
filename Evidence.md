### Examination Environment and Attached Storage

The forensic workstation was examined prior to acquisition to identify all connected storage devices. Dedicated drives were used for evidence storage and analysis to prevent cross-contamination and ensure forensic integrity.

![Forensic workstation environment and attached storage devices](Assets/screenshots/lab1-environment-and-attached-drives.png)

To independently validate file integrity, cryptographic hash values were generated using HashCalc. This step provided an additional verification method outside of FTK Imager and demonstrated consistency across forensic tools.

Both MD5 and SHA-1 hashes were calculated for the validation file and recorded to establish a baseline for integrity verification.

![HashCalc MD5 and SHA1 hash validation](Assets/screenshotslab1-hash-validation-hashcalc-md5-sha1.png)

To further demonstrate artifact-level integrity verification, cryptographic hashes were also generated for the validation text file created during the lab exercise. This ensured that individual evidence files remained unchanged after creation.

MD5 and SHA-1 hash values were calculated using HashCalc and recorded for verification purposes.

![HashCalc MD5 and SHA1 validation of text file](Assets/screenshots/lab1-hash-validation-textfile-hashcalc-md5-sha1.png)

## Analysis Environment Documentation

The system used to perform evidence acquisition and analysis was documented to establish environmental context and support reproducibility. Recording system specifications helps validate that forensic tools were executed in a controlled and appropriate environment.

The following screenshot captures the Windows system configuration, including device specifications, operating system architecture, and enabled security controls at the time of analysis.

![Windows system specifications used for forensic analysis](Assets/screenshots/lab1-analysis-environment-windows-system-about.png)
