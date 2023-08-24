# winapps - NCPA Windows Build Dependencies

This repository contains the necessary dependencies for building NCPA on Windows.

## Getting Started

1. Navigate to the `windows` folder and clone this repository.
2. If you are Cody, Ethan, or me, you'll know what to do.
3. Cheers! 🍻

**Note:** The Win32OpenSSL and VCForPython files are too large for GitHub and come split into multiple zip files.

## Merging Split Files for VCForPython

To merge the split files for VCForPython, use the following command:

```bash
copy /b VCForPython27.msi.001 + VCForPython27.msi.002 + VCForPython27.msi.003 + VCForPython27.msi.004 + VCForPython27.msi.005 + VCForPython27.msi.006 + VCForPython27.msi.007 + VCForPython27.msi.008 + VCForPython27.msi.009 VCForPython27.msi
