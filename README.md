# TWRP device tree for Infinix Note 11 Pro (X697)

## Status

Specs [here](https://twrp.me/faq/OfficialMaintainer.html)
The tester [Simich07](https://4pda.to/forum/index.php?showuser=1671401) only install boot-x697-A11-20220928-1932.img test file to know if TWRP can start.
Test with boot-x697-A11-20220928-1932.img show in the screen. Not other test was made.

Next branch android-11 has encrypt/decrypt files and option to more test with that.


## Building

```bash
source build/envsetup.sh
lunch twrp_x697-eng
mka bootimage
```

