# HID Remapper: Dvorak typing, QWERTY modifiers

Keyboard layout for [HID Remapper](https://www.remapper.org/) that mimics macOS “Dvorak — QWERTY ⌘”.
- Regular typing is Dvorak.
- Any chord that includes Cmd/Alt/Ctrl stays QWERTY so shortcuts match printed legends.

## Files
- `Dvorak-CmdQwerty.json` — HID Remapper config with the Dvorak typing/QWERTY modifier mapping.

## Usage
1) Open [remapper.org](https://www.remapper.org/) or the HID Remapper web UI with your device connected.
2) Load the config: `Open` → select `Dvorak-CmdQwerty.json`.
3) Flash/apply to the device. Shortcuts should now behave like macOS Dvorak-QWERTY ⌘.

## Notes
- If you customize keys, keep modifier combos (Cmd/Alt/Ctrl) on the QWERTY layer so shortcuts remain aligned with keycaps.
- Tested with HID Remapper firmware v18 config format.
