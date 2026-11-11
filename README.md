# 🔍 Digital Forensics Lab: Evidence Acquisition & Artifact Analysis

## 📌 Project Overview
A comprehensive, end-to-end simulated Digital Forensics investigation (Case ID: `DF-2026-001`) focused on evidence creation, integrity preservation, forensic disk acquisition, artifact analysis, and reporting.

The goal of this project was to simulate an enterprise incident scene, acquire evidence without altering original files, and analyze system artifacts to detect disguised files, hidden credentials, and user activity timelines.

## 🛠️ Tools & Technologies Used
- **Forensic Acquisition:** FTK Imager 4.5.0.3 (`.E01`, `.ad1` formats)
- **Artifact Analysis:** Autopsy 4.23.1
- **Integrity Verification:** SHA-256 Hashing via PowerShell & CertUtil
- **Disk Management:** Windows DiskPart (VHDX Virtual Disk Creation & Managed Deletion)
- **Documentation:** Markdown & Automated HTML Reporting


## 📁 Repository Structure
Digital-Forensics-Lab/
├── 01-Case-Documentation/    # Incident scope & case details (case-details.md)
├── 02-Original-Evidence/      # Synthetic evidence files (PDF, PNG, Log, Hidden)
├── 03-Forensic-Images/        # FTK Imager acquired disk images (.E01 & .ad1 metadata)
├── 04-Hash-Records/           # SHA-256 baseline & verification logs
├── 05-Autopsy-Cases/          # Autopsy investigation database & HTML reports
├── 06-Analysis-Results/       # Extracted artifacts & CSV summary sheets
├── 07-Screenshots/            # Evidentiary proof (FTK match, Hex view, Timelines)
└── 08-Final-Reports/          # Final Comprehensive Forensic Investigation Report
