# Thirtytwo Bit Systems — logo assets

SVG is the master. Scale only; never recolour or rotate.

| File | Use |
|---|---|
| 32bs-mark.svg | Primary, on light backgrounds. Above ~32px. |
| 32bs-mark-inverse.svg | On ink / dark backgrounds. |
| 32bs-mark-mono-black.svg / -white.svg | One colour: silkscreen, laser, stamp, fax-grade print. |
| 32bs-mark-small.svg / -inverse.svg | Below ~32px — pins dropped, traces straightened. |
| 32bs-appicon.svg | Square icon with background; use for app icon / social avatar. |
| 32bs-appicon-leads.svg | Rounded badge on ink, package inverted so all twelve leads read. Use wherever the icon sits on an unknown or white background — GitHub profiles, README headers, avatars. |
| 32bs-lockup-horizontal.svg / -inverse.svg | Mark + name, side by side. |
| 32bs-lockup-stacked.svg / -inverse.svg | Mark + name, centred. |
| png/ | Raster renders: 512 mark, 180 app icon, 32 + 16 favicons. |

Clearspace: one quarter of the mark's width on all sides.
Colours: ink #1A1C1F, white #FFFFFF, pin-1 blue #6C97F2.

## Web use
```html
<link rel="icon" href="/32bs-mark-small.svg" type="image/svg+xml">
<link rel="icon" href="/favicon-32.png" sizes="32x32">
<link rel="apple-touch-icon" href="/32bs-appicon-180.png">
```
In the header, inline the SVG so it inherits colour and stays crisp.

Lockup type is live text (Space Grotesk 700 / IBM Plex Mono). For print or logos sent outside, open the SVG and convert text to outlines.
