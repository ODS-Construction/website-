# ODS Construction — brand assets

Vector artwork traced from `logo.jpg` (1600x800). Geometry verified against the
source at sub-pixel accuracy; all contours are in a single path using
`fill-rule="evenodd"` so counters and column gaps stay open.

## Files

### SVG — use these wherever possible
| File | Use |
|---|---|
| `ods-logo-navy.svg` | Primary. Light backgrounds. `#10264A` |
| `ods-logo-white.svg` | Reversed. Dark panels, over photography |
| `ods-logo-black.svg` | One-colour reproduction: permits, stamped drawings, scans, embroidery |
| `ods-logo-current.svg` | Web embedding; inherits CSS `color` |
| `ods-icon-*.svg` | Mark only, no wordmark. Nav bar, app icon, social avatar |

### PNG — transparent, for anything that can't take SVG
`ods-logo-{navy,white,black}-{2400,1200,600}.png`, `ods-icon-{navy,white}-{1024,512,256}.png`

Alpha is derived from the source luminance, so edges stay clean on any background.

### Favicon
`../favicon.svg` — navy tile, mark knocked out in white. Tile rather than a
transparent mark so it stays visible on dark browser tabs.

## Colour
Navy `#10264A` — matches the site's brand navy. Do not use pure black on the
website; black is for one-colour print reproduction only.

## Known limit
Below roughly 24px the fan rays merge visually — unavoidable with a mark this
fine. If a small-size variant is needed (favicon, embroidery, app icon), the
rays need thickening and thinning in count as a deliberate redraw.

## Regenerating
`preview.html` is a self-contained contact sheet — open it in a browser.
