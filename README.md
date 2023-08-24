# winapps - NCPA Windows Build Dependencies

This repository contains the necessary dependencies for building NCPA on Windows.

## Getting Started

1. Navigate to the `windows` folder and clone this repository.
2. If you are Cody, Ethan, or me, you'll know what to do.
3. Cheers! 🍻

**Note:** The Win32OpenSSL and VCForPython files are too large for GitHub and come split into multiple files.

## Merging Split Files for VCForPython
**Note:** Must be done in CMD not PowerShell! - cd into /winapps and run the following commands 

To merge the split files for VCForPython, use the following command:
```bash
copy /b VCForPython27.msi.001 + VCForPython27.msi.002 + VCForPython27.msi.003 + VCForPython27.msi.004 + VCForPython27.msi.005 + VCForPython27.msi.006 + VCForPython27.msi.007 + VCForPython27.msi.008 + VCForPython27.msi.009 VCForPython27.msi

del VCForPython27.msi.0*

```

## Merging Split Files for Win32OpenSSL

To merge the split files for Win32OpenSSL-3_1_2, use the following command:

```bash
copy /b Win32OpenSSL-3_1_2.msi.001 + Win32OpenSSL-3_1_2.msi.002 + Win32OpenSSL-3_1_2.msi.003 + Win32OpenSSL-3_1_2.msi.004 + Win32OpenSSL-3_1_2.msi.005 + Win32OpenSSL-3_1_2.msi.006 + Win32OpenSSL-3_1_2.msi.007 Win32OpenSSL-3_1_2.msi

del Win32OpenSSL-3_1_2.msi.0*
```
🗻🗾🍱
