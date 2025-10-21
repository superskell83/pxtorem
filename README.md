# Install PX to REM VSIX Extension

1. Open the folder where px-to-rem-1.0.0.vsix is downloaded in VS Code.

2. Right-click on px-to-rem-1.0.0.vsix.

3. Select "Install Extension VSIX."

# PX to REM Converter

Convert px values to rem directly in VSCode via:

- Right-click → “Convert PX → REM”
- Shortcut: `Ctrl + Alt + Shift + W`

## Settings

You can adjust conversion base and precision in `settings.json`:

```json
{
  "pxToRem.baseSize": 16,
  "pxToRem.decimals": 3
}
```
