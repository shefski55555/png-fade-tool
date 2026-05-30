# PNG Fade Tool

A lightweight, browser-based tool for applying inner and outer fade effects to images, exported as transparent PNGs. No install, no server, no dependencies — just open the HTML file.

## Features

- **Inner fade** — edges fade inward to transparent, with adjustable size and softness
- **Outer fade** — center fades outward to transparent, creating a hole or halo effect
- **Square or circular** fade shape for both inner and outer fades
- **Global opacity** — uniformly scale the transparency of the entire image
- **Preview background** — choose a solid colour or checkerboard to preview transparency (not included in the export)
- **Low-res preview mode** — fast live preview using a downscaled copy; download is always full resolution
- **Full resolution preview** toggle for pixel-accurate feedback
- All processing is done entirely in the browser — no data is uploaded anywhere

## Usage

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
2. Drop an image onto the upload area or click to browse
3. Adjust the fade settings using the sliders or type values directly
4. Download the result as a transparent PNG

## Browser support

Requires a modern browser with support for the Canvas API, `getImageData`, `toBlob`, and the File API. The tool will display a clear error message if any required feature is unavailable.

## Performance

The live preview renders at a reduced resolution by default for responsiveness. The downloaded PNG is always processed at the original image's full resolution. Enable **Full resolution preview** in the settings if you need pixel-accurate feedback while editing.

## Credits

Written by [Claude](https://claude.ai) (Anthropic).
