# Build Vars Spoofing

Build Vars Spoofing. **Android 8.1 or above is required**.

## Usage

1. Flash this module and reboot.
2. Enjoy!

You can try enabling/disabling Build variable spoofing by creating/deleting the file `/data/adb/build_var_spoof/pif.json`.

Build Vars Spoofing will automatically generate example config props inside `/data/adb/build_var_spoof/pif.json` once created, on next reboot, then you may manually edit your spoof config.

Here is an example of a spoof config:

```
{
  "ID": "AP41.240823.009",
  "BRAND": "google",
  "DEVICE": "oriole",
  "FINGERPRINT": "google/oriole_beta/oriole:15/AP41.240823.009/12329489:user/release-keys",
  "MANUFACTURER": "Google",
  "MODEL": "Pixel 6",
  "PRODUCT": "oriole_beta",
  "SECURITY_PATCH": "2024-09-05"
}
```

## Acknowledgement

- [PlayIntegrityFix](https://github.com/chiteroman/PlayIntegrityFix)
- [LSPosed](https://github.com/LSPosed/LSPosed)
