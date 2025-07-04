# BitLocker is a Microsoft Windows security and encryption feature included with certain Windows versions.

- BitLocker enables users to encrypt everything on the drive Windows is installed on, protecting that data from theft or unauthorized access.
- Microsoft BitLocker improves file and system protections by mitigating unauthorized data access.

[Tech Target](https://www.techtarget.com/searchenterprisedesktop/definition/BitLocker)

# When/How Bitlock started (https://en.wikipedia.org/wiki/BitLocker)

BitLocker originated as a part of Microsoft's Next-Generation Secure Computing Base architecture in 2004.
It was tentatively codenamed *Cornerstone* and was designed to protect information on devices.
Another feature *Code Integrity Rooting* was designed to validate the integrity of Microsoft Windows boot and system files.
BitLocker was briefly called **Secure Startup** before Windows Vista's release to manufacturing.

https://www.youtube.com/watch?v=iX8QC2pRuYM

# How Bitlocker works

BitLocker uses a specialized chip called a **Trusted Platform Module (TPM)**
TPM stores Rivest-Shamir-Adleman encryption keys specific to the host system for hardware authentication.

https://www.techtarget.com/searchenterprisedesktop/definition/BitLocker


## How to Enable Bitlocker
- Enabling BitLocker using hardware-based encryption
  - Check if your device has TPM support to enable BitLocker
  - Enable BitLocker

- Enabling BitLocker using software-based encryption (without TPM support)
  - Activate startup authentication with Local Group Policy Editor
  - Enable BitLocker

[How to](https://superops.com/blog/bitlocker-encryption-windows-10)

# Why you need Bitlocker

BitLocker ensures that only you (or someone with whom you’ve shared your BitLocker recovery key) can access the files on your PC.

