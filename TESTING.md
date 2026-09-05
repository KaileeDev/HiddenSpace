# HiddenSpace beta testing checklist

Please test only on a device you are comfortable troubleshooting and make sure you can disable or uninstall the tweak if SpringBoard becomes unstable.

## Device information

Include:

- Device model
- Exact iOS version
- Jailbreak name and version
- HiddenSpace version

## Functional checklist

### Home Screen

- Selected apps disappear from the Home Screen.
- Hidden apps cannot be tapped from their old positions.
- Nearby icons remain correctly positioned.
- Entering and exiting edit mode does not reveal or misplace hidden apps.

### Dock

- Selected Dock apps disappear immediately.
- Hidden Dock apps cannot be tapped from their old positions.
- Remaining Dock icons stay correctly positioned.
- Behavior remains correct after opening/closing apps and after a SpringBoard restart.

### Folders

- Hidden apps disappear inside opened folders.
- Folder cover previews do not reveal hidden apps.
- Remaining folder icons compact correctly where supported.
- Opening and closing unrelated folders does not cause visible icons to jump or animate through hidden slots.

### Hidden Space

- Two-finger spread opens Hidden Space where supported by the current build.
- Two-finger pinch closes it.
- Selected applications appear correctly.
- Adding/removing applications updates the selection correctly.

### Authentication

If enabled:

- Face ID / Touch ID appears appropriately for the device.
- Failed or cancelled authentication does not expose the protected app grid.
- Locking/backgrounding the device closes or relocks the protected view as expected.

### Disable / uninstall safety

- Disabling HiddenSpace restores normal icon visibility.
- Removing HiddenSpace restores normal SpringBoard presentation.
- No application is uninstalled or removed from LaunchServices.

## Report format

Example:

```text
Device: iPhone 14 Pro Max
OS: iOS 16.6
Jailbreak: Dopamine <version>
HiddenSpace: <version>
Home Screen: PASS / FAIL
Dock: PASS / FAIL
Folders: PASS / FAIL
Hidden Space: PASS / FAIL
Authentication: PASS / FAIL / N/A
Disable restore: PASS / FAIL
Notes: ...
```

Please attach a short screen recording and relevant SpringBoard logs when reporting a reproducible failure.
