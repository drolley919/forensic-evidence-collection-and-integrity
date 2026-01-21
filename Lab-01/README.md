# Lab 01 – Forensic Evidence Collection & Integrity

## Case Overview
This case demonstrates foundational digital forensics principles focused on **forensic evidence acquisition, preservation, and integrity validation**. The objective was to collect system artifacts from a Windows environment while maintaining evidentiary soundness and documenting procedures consistent with industry-standard forensic practices.

This investigation emphasizes repeatable methodology, cryptographic hashing, and documentation suitable for incident response, legal review, or security operations contexts.

---

## Objectives
- Establish a controlled forensic analysis environment
- Acquire system artifacts using forensically sound methods
- Validate evidence integrity through cryptographic hashing
- Document findings in a structured, case-based format

---

## Environment & Tools
**Operating Systems**
- Windows 10 (target system)
- Kali Linux (analysis workstation)

**Forensic Tools**
- FTK Imager
- Autopsy
- Native Windows utilities
- Cryptographic hashing utilities (MD5/SHA)

---

## Evidence Collected
Evidence collected during this case includes:
- System metadata and configuration artifacts
- File system artifacts relevant to system state validation
- Cryptographic hash values generated at acquisition time

Detailed evidence handling procedures and hash values are documented in  
[`Evidence.md`](./Evidence.md).

---

## Key Skills Demonstrated
- Forensic evidence acquisition and preservation
- Hash-based integrity verification
- File system artifact handling
- Professional forensic documentation
- Chain-of-custody–aware reporting structure

---

## Artifacts & Documentation
- **Executive Summary:** [`Executive-Summary.md`](./Executive-Summary.md)
- **Evidence Handling & Hashes:** [`Evidence.md`](./Evidence.md)
- **Technical Analysis:** [`Analysis.md`](./Analysis.md)
- **Findings:** [`Findings.md`](./Findings.md)
- **Recommendations:** [`Recommendations.md`](./Recommendations.md)
- **Supporting Screenshots:** [`Assets/screenshots/`](./Assets/screenshots)

---

## Notes
This case is presented as part of a broader digital forensics portfolio intended to demonstrate applied DFIR skills in a professional, recruiter-facing format.
