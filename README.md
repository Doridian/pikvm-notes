# pikvm-notes

This is a document of several notes I encountered with my PiKVM device

## EDID notes

- If you want to use v4p (passthru), this requires RGB/BGR mode, not YUV

- It seems the TC3... chip in PiKVM units does not do RGB capture at resolutions > ~ 1024x768 / 720p

- Therefor the EDID included here is limited to 1024x768 and smaller 4:3 resolutions

- 16:9 resolutions have been removed as my local screen is 4:3
