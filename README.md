# Pixel-boot-animation-magisk
This simple Magisk module applies boot animations of Pixel phones. New Google Pixel (from 9 series on) Gemini boot animation and legacy will both be available here.

The Google logo can only be used if you have an existing partnership or sponsorship and you’ve reached out to your Google contact to secure formal approval from the Google brand team. Please consult [Google Brand Resource Center](https://about.google/brand-resource-center/).

*Legacy boot animation is available now in releases*

**ONLY VERIFIED ON LINEAGE OS 22.1 WITH APATCH**

## Disclaimer

* I am not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.

* Please do some research if you have any concerns about this module before flashing it!

* YOU are choosing to make these modifications; I AM NOT RESPONSIBLE for any consequences.

## Mechanism

The Android system sources `/system/product/media/bootanimation.zip` and `/system/product/media/bootanimation-dark.zip` for boot animation (not to be mistaken with manufacturers' boot splash Logo).

This module replaces files mentioned above to deliver Pixel phones' boot animation to AOSP-based custom ROMs, not all of them sources these locations and works though...

## Known issues

### Screen ratio may be wierd

Boot animation files are extracted from Google Pixel 9 (for the Gemini boot animation) and Google Pixel 8 (for the legacy boot animation, the Monet Engine coloured "G" Logo), so it might have wierd screen ratio on "certain" devices, such as Sony Xperia with its 21:9 screen.

### You tell me.