# STIG-Remediations
A collection of STIG and vulnerability remediations (before/after evidence, notes, and scripts) performed in a cyber range environment.
## Before Remediation
- Vulnerability detected: Windows Defender signature outdated
- Proof: Signature Timestamp = Jan 6, 2025
- Source: Tenable screenshot (see below)
<img width="1847" height="497" alt="image" src="https://github.com/user-attachments/assets/1a1b382b-803f-4635-8c7c-335f9d1c8292" />
## Remediation Steps (Planned/Executed)
1. Update Windows Defender signatures (via Windows Update or `MpCmdRun.exe -SignatureUpdate`).
2. Verify Defender definitions are current.
3. Re-run Tenable scan to confirm.

---

## After Remediation
- (placeholder – will add screenshot once fixed and rescanned)

![After Screenshot](Windows-Defender-Signature-Update/DefenderSignature-After.png)




