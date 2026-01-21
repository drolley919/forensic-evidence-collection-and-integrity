## Examination Environment & Evidence Integrity Validation

### Examination Environment and Attached Storage
Prior to evidence acquisition, the forensic workstation was examined to identify all connected storage devices. Dedicated storage media were used exclusively for evidence handling and analysis to prevent cross-contamination and preserve forensic soundness.

This step ensured that no unintended read/write operations occurred on non-evidence media and that the examination environment met baseline forensic handling standards.

![Forensic workstation environment and attached storage devices](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-01/Assets/screenshots/lab1-environment-and-attached-drives.png)

---

### Cryptographic Hash Validation (Tool Cross-Verification)
To independently validate file integrity, cryptographic hash values were generated using **HashCalc** in addition to FTK Imager. This provided cross-tool verification and demonstrated consistency between forensic utilities.

Both **MD5** and **SHA-1** hash values were calculated and recorded to establish a verifiable integrity baseline prior to further analysis.

![HashCalc MD5 and SHA-1 validation](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-01/Assets/screenshots/lab1-hash-validation-hashcalc-md5-sha1.png)

---

### Artifact-Level Integrity Verification
To further demonstrate evidence integrity at the artifact level, cryptographic hashes were generated for the validation text file created during the lab exercise. This confirmed that individual evidence files remained unchanged after creation and during handling.

MD5 and SHA-1 hash values were calculated using HashCalc and documented to support repeatable verification and auditability.

![Text file hash validation using HashCalc](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-01/Assets/screenshots/lab1-hash-validation-textfile-hashcalc-md5-sha1.png)

---

## Analysis Environment Documentation

The system used to perform evidence acquisition and analysis was documented to establish environmental context and support reproducibility. Recording system specifications helps demonstrate that forensic tools were executed in a controlled and appropriate environment.

The following screenshot captures the Windows system configuration at the time of analysis, including device specifications, operating system architecture, and enabled security controls.

![Windows system specifications used for forensic analysis](https://github.com/drolley919/forensic-evidence-collection-and-integrity/blob/main/Lab-01/Assets/screenshots/lab1-analysis-environment-windows-system-about.png)
