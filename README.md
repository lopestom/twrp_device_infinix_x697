# TWRP device tree for Infinix Note 11 Pro (X697)

## Status

Specs [here](https://twrp.me/faq/OfficialMaintainer.html)

The tester [Simich07](https://4pda.to/forum/index.php?showuser=1671401) only install `boot-x697-A11-20220928-1932.img` test file to know if TWRP can start.

Some tests was made: Enc_Dec working. Removed one file with 1.36MB because not need and removing that, the Magisk can install with more free size.

Issue: unlocking screen not work - Hide TW_SCREEN_BLANK_ON_BOOT: Maybe this cause touch screen issue when unlocking screen.

This branch android-11 has ***encrypt/decrypt*** files and option to more test with that.

****2022-10-12****: Changes to made new version TWRP3.7.0

## Building

```bash
source build/envsetup.sh
lunch twrp_x697-eng
mka bootimage
```

