# Android 6.0.0 Extracts (Nexus 5X / bullhead)

This repository contains files extracted from Android 6.0.0 (Marshmallow) for the Nexus 5X (bullhead).

Source factory image:
https://dl.google.com/dl/android/aosp/bullhead-mda89e-factory-d716b566.zip

---

Extraction process:

- boot.img was extracted using binwalk:
  binwalk -e boot.img

- system.img was extracted using foremost:
  foremost -i system.img

The extraction was done directly on the raw images.

---

Releases:
https://github.com/PyCSharp/Android-6.0.0-Extracts/releases/

All files come from publicly available Google factory images.
No files were modified.
