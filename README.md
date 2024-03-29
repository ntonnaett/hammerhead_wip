# Hammerhead links

## General
- [Devicetree Sprecification](https://github.com/devicetree-org/devicetree-specification/releases/tag/v0.3)
- [masneyb’s Nexus 5 tree](https://github.com/masneyb/linux)
- [flto’s MSM8974 tree](https://github.com/flto/linux/tree/msm8974)
- [masneyb’s nexus-5-upstream page](https://masneyb.github.io/nexus-5-upstream/)
- [masneyb’s nexus5-upstream/TODO](https://masneyb.github.io/nexus-5-upstream/TODO.html)
### Components
- [Components: smartdroid.de](https://www.smartdroid.de/nexus-5-detaillierte-auflistung-aller-verbauten-komponenten/)
- [Components: deviceinfohw.ru](http://deviceinfohw.ru/devices/variants.php?model=Nexus%205&set_brand=google&set_vendor=LGE)
- [Hammerhead schematics](https://phonelumi.com/lg-nexus-5-d820-schematics-manual/)

## WCD9320 (Audio Driver)
- [PMOS Metaissue](https://gitlab.com/postmarketOS/linux-postmarketos/-/issues/3)
- [PMOS MSM8974: Fp2: Initial audio (without WCD9320?)](https://gitlab.com/postmarketOS/pmaports/-/merge_requests/38?commit_id=702e43cbf5872599ba7235a09981fe42fc81bb6c)
- [Google downstream](https://android.googlesource.com/kernel/msm/+/android-msm-hammerhead-3.4-kk-fr2/sound/soc/codecs/wcd9320.c)
- [LineageOS downstream wcd9320.c](https://review.lineageos.org/c/LineageOS/android_kernel_sony_msm8974/+/106522/2/sound/soc/codecs/wcd9320.c)
- [Add routes from slimbus ports to IIR](http://visa.lab.asu.edu/gitlab/fstrace/android-kernel-msm-hammerhead-3.4-marshmallow-mr3/commit/6a8a7c82b54249a88df0c8ace310536d0cc05ea7)
- [Don't enable unnecessary audio path](http://visa.lab.asu.edu/gitlab/fstrace/android-kernel-msm-hammerhead-3.4-marshmallow-mr3/commit/070620fa982b6a0e1f7a3ff397c5de37b934123b)
- [CVE-2016-5858](https://nvd.nist.gov/vuln/detail/CVE-2016-5858)
- [CVE-2020-3685](https://secalerts.co/cve/CVE-2020-3685)
- [Vulnerabilities on WCD9320](https://secalerts.co/vulnerabilities/qualcomm/wcd9320)
### WCD9320 Hacks
- [flto’s WCD9320 stuff](https://github.com/flto/linux/commit/0af04bc3a5abb66a18038131df88fdd216cee244)
- [Swapnil133609’s WCD9320 stuff](https://github.com/Swapnil133609/Android-Kernel-Patches/blob/master/flar2/0055-sound-control-3.x-Initial-GPL-release-for-WCD9320-Au.patch)
- [Cocafe’s custom kernel for Xperia Z2](https://github.com/cocafe/xperia-z2_kernel_cocore-l)
  - [WCD9320 Taiko Audio Codec Control (hints for Cocafe’s kernel)](https://github.com/Grarak/KernelAdiutor/issues/225)
  - [Xda-developers (other hints for Cocafe’s audio codec)](https://forum.xda-developers.com/t/kernel-z1c-5-0-5-1-f2fs-advanced-kernel-v19-0-2017-03-25.3096060/page-2#post-62125592)
- [Android kernel mod with WCD9320 hacks](https://forum.xda-developers.com/t/kernel-development-pdesireaudio-maximum-audio-power-for-snapdragon-devices.3429491/)
### Other audio codecs for comparison
- [Upstream support for WCD934x](https://lore.kernel.org/linux-devicetree/20191219103153.14875-1-srinivas.kandagatla@linaro.org/)
- [WCD9340 on SDM845: Enable audio on SDM845](https://gitlab.com/sdm845-mainline/linux/-/commit/b0484a0f4f80367a87fa7c24ca045921e3140f34)
- [WCD9335 Audio Codec Device Specifications](https://developer.qualcomm.com/download/sd820e/wcd9335-audio-codec-device-specification.pdf)
- [WCD9311 Audio Codec Device Specifications](https://developer.qualcomm.com/download/sd600/wcd9311-audio-codec-device-specification.pdf)

## Graphics / Adreno 330
- [DSI Panel driver tutorial](https://gitlab.freedesktop.org/freedreno/freedreno/-/wikis/DSI-Panel-Driver-Porting)
