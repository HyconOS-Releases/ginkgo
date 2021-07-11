## Changelogs for Redmi Note 8/8T (Ginkgo/Willow)

## July changelog (11-07-2021)
* Updated stock blobs from MIUI 21.7.5
* Updated CAF blobs from LA.UM.9.11.r1-03900-NICOBAR.0
* Kernel upstreamed to 4.14.238
* Fixed tiktok, QQ and other apps crash due to vulkan
* Fixed magisk issue with some banking apps
* Added LED indicator for offline charging
* Reduce schedtune boosting for lesser heat
* Freed some RAM from useless virtual framebuffer
* Switched to QTI health implementation

## May changelog (18-05-2020)
* Switched to dipper fp
* Updated blobs to MIUI 21.4.28
* Set up/down_rate_limit_us to 1000us
* Updated CAF blobs from LA.UM.9.11.r1-03200-NICOBAR.0
* Updated WifiOverlay from LA.UM.9.1.r1-09100-SMxxx0.0
* Updated auto brightness configuration from stock
* Switched to oss perf hal
* Lower little cluster min freq to 864Mhz
* Enable conservative pl boosting
* Sync scroll boost freqs with CPU input boost
* Tune perfboostsconfig for performance
* Import QTI perf configs from stock
* Fixed 5ghz wifi issue with a11 fw
* Fixed Gphotos "Device is too hot" issue
* Kernel upstreamed to 232
* Merged LA.UM.9.1.r1-09600-SMxxx0.0 CAF tags
* Added compat (32bit) vdso
* Added CPU input and Devfreq boosts
* Added kernel space battery saver

## April changelog (16-04-2020)
* Updated redfin fp/desc to april
* Imported new Xiaomi Parts
* Added MiCam Watermark for Hycon Os
* Upstreamed QS kernel kernel to V4.14.230
* Fast charging on chinese variants maybe fixed
* Merged pie chromatix libs for better cam quality

## March changelog (28-03-2020)
* Switched to redfin march 2021 fp
* Kernel upstreamed to 227
* Switched to pixel charger animation
* Fine tuned notch cutout
* Updated to Miui R blobs (21.3.3)
* Some performance tune ups
* Switched to Qti Bt
* Updated CAF blobs from LA.UM.9.11.r1-02800
* Fixed camera freeze in some apps and camera lens switching delay
* Fixed voip/mic issues in some apps
* Switched to new QTI thermal HAL
* Attempted to fix screen blackouts under sunlight/heat
* Improved rounded corners and fixed hide cutout option and GPS configs
* Added support for willow hwversion 18.31.0
