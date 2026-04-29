# SOP 01: Secure Remote Workstation Deployment
**Version:** 1.0
**Status:** Active
**Scope:** IT Engineering / Helpdesk

## 1. Purpose
To standardize the provisioning of corporate laptops for remote employees, ensuring 100% compliance with security protocols and hardware reliability.

## 2. Hardware Preparation
1. **Physical Audit:** Check for chassis damage and screen integrity.
2. **BIOS Configuration:** - Enable **TPM 2.0**.
- Disable **Secure Boot** during imaging (re-enable after).
- Set BIOS Supervisor Password to prevent hardware tampering.

## 3. OS Deployment & Security
1. **Imaging:** Deploy Windows 11 Pro via Microsoft Intune/PXE.
2. **Disk Encryption:** Activate **BitLocker**. Recovery keys must be automatically backed up to Azure AD.
3. **MFA Setup:** Force enrollment in Microsoft Authenticator upon first login.

## 4. Verification Checklist
- [ ] BitLocker is "On".
- [ ] VPN Client (Cisco/AnyConnect) is pre-configured.
- [ ] CrowdStrike/SentinelOne is reporting "Active".Recovery keys must be automatically backed up to Azure AD.
3. MFA Setup: Force enrollment in Microsoft Authenticator upon first login.

 4. Verification Checklist
 [ ] BitLocker is "On".
 [ ] VPN Client (Cisco/AnyConnect) is pre-configured.
 [ ] CrowdStrike/SentinelOne is reporting "Active".
