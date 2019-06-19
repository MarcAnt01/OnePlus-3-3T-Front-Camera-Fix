# OnePlus 3/3T Front Camera fix

# THE CODE IN THIS REPO ISN'T UP-TO-DATE, TAKE A LOOK [HERE](https://github.com/Magisk-Modules-Repo/Oxy-ify)

This module has to be used with a modified Google Camera, recommended versions for OnePlus 3/3T are the ones from [Arnova8G2](https://www.celsoazevedo.com/files/android/google-camera/dev-arnova8G2/) and [Toylan009](https://www.celsoazevedo.com/files/android/google-camera/dev-tolyan009/); you can also use the ones from [Urnyx05](https://www.celsoazevedo.com/files/android/google-camera/dev-urnyx05/) and [MarcAnt01](https://www.celsoazevedo.com/files/android/google-camera/dev-marcant01/).

On OnePlus 3T only (not on 3) it increases the resolution of photos taken with front camera from 4 MP to 16 MP.
On GCams from some devs (not the ones above) it enables HDR+, portrait and fixes green tint on front camera both on 3 and 3T.

## How about compatibility?

This module works with Magisk 17.0+ and Android 8.0+ (both Oxygen OS and Custom Roms are supported).

## How does it work?

It fixes some libraries which are placed in ``` system/vendor/lib ```

## Who realised that?

- [Savitar](https://forum.xda-developers.com/member.php?u=377973) aka Defcomg realised patched libraries;
- [Arnova8G2](https://forum.xda-developers.com/member.php?u=4860033) made a Magisk Module with the libraries;
- [MarcAnt01](https://forum.xda-developers.com/member.php?u=9262827) updated to the new Magisk installer, added minor improvements and device check.

Other contributors:
- [3liteking](https://forum.xda-developers.com/member.php?u=7606633) and [CrashOverride1995](https://forum.xda-developers.com/member.php?u=4691396) for some boot script logic and SELinux fixes from another module, which have been used here;
- [S4turno](https://forum.xda-developers.com/member.php?u=4487956) for previous template updates to the module.
