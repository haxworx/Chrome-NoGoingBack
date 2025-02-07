# No Going Back Patch for Chrome/Chromium

## Description
This patch ensures that users cannot navigate back in Chrome/Chromium browsers. Once applied, there is **no going back**—literally.

## Installation Instructions
To apply the patch, navigate to the Chromium source directory and run:

```sh
patch -p1 < chromium_no_going_back.diff
```

## Disclaimer
Use this patch with caution. Once applied, there is **no going back**.
