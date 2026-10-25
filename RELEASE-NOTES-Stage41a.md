# Stylish Immersion 1.0 — Stage41a Test Candidate

**Status: Experimental / headset validation pending.**

## Installation
1. Install Talemann's RE4 PCVR **2.1.5** first and verify that it works.
2. Install **ViGEmBus**.
3. Close Resident Evil 4 and back up your existing working configuration and personal JSON edits.
4. Disable any older Stylish Immersion package, retired grapple overlay, and separate Free Reload Speed overlay.
5. Install the **original Fluffy-compatible ZIP** with Fluffy Mod Manager. Do **not** use GitHub's source-code ZIP.
6. Enable the mod and restart Resident Evil 4.

## Included features
- Offhand and dual-pistol interactions
- Extra holsters and grip looting
- Contextual punches and physical grenade pin pulling
- Calibrated recoil and reload JSON overrides
- Free Reload Speed 0.2
- Stage41a LT prompt observer adjustment, retaining the Stage41 Special Rocket Launcher behavior

## Important compatibility notes
- This package replaces **dinput8.dll** and is **not a standalone plugin**.
- Its custom DLL derives from a 2.1.4 codebase; parity with private changes in Talemann 2.1.5 is unverified.
- Local tests passed, but the Stage41a LT fix is **not yet verified in live headset operation**.
- Original Grapple 0.1 targeting, UI size, and right-stick vertical limitation remain; hold A is a fallback.

## Troubleshooting
For the Separate Ways LT prompt, release LT, then press LT with the R1 prompt visible. If the input fails, collect `re2_framework_log.txt` after one visible-prompt press. To roll back, disable this package and restore your previous working DLL/package.

## Credits
**Talemann** — original RE4 PCVR mod and DLL foundation, with redistribution permission confirmed by the project maintainer. **Rankiseth** — Stylish Immersion modifications and packaging.

**Distribution:** The installable ZIP must be attached as a GitHub Release asset. This Markdown file is documentation only.
