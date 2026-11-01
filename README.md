# Stitch Atelier

A free cross stitch pattern designer that runs entirely in the browser, built around the **Rico Design Sticktwist** color range (001–296 plus the metallic threads).

It is a single file, `index.html`. There is nothing to install and no server: open the file, or host it with GitHub Pages.

## What it does

- Draw patterns stitch by stitch: paint, erase, pick, line, rectangle and ellipse, fill, select / move / flip / rotate, half stitches, backstitch, mirror drawing, undo and redo.
- Four views: threads, symbols, symbols on color, and flat blocks. Light and dark theme follow your system.
- **Photo to pattern:** load a picture, crop it, choose the size in stitches and the number of colors. The importer picks the best-fitting real Rico colors for that count, so every smaller palette is a subset of a larger one. A "Best fit" button suggests the count after which extra colors barely help, and a match meter shows how close the result is to the best possible. Optional dithering, speck removal, background removal and gentle auto-enhance.
- **My collection:** mark the Rico colors you own. The color picker can show only your colors (or all of them), the photo importer can build the pattern from your collection only, and colors you would still have to buy are marked in the palette and materials list. The collection is saved in your browser, and you can type or paste a list of Rico numbers.
- Every color shows its Rico number with the DMC and Anchor equivalents. Search by any of the three, or match an arbitrary color to the nearest Rico colors.
- Materials tab with stitch counts per color and an estimate of the skeins needed (fabric count and strands are adjustable).
- Export a printable **PDF** (cover, color legend, chart pages), a **PNG** chart, a **CSV** material list, or a project file (`.json`) you can open again later.
- English and German interface.

Your patterns are stored only in your browser (local storage). Photos are processed on your device and never uploaded. Use **File → Save as file** for a backup.

## Run it

Open `index.html` in any current browser.

To publish it as a website with GitHub Pages: repository **Settings → Pages → Build and deployment**, source **Deploy from a branch**, branch `main`, folder `/ (root)`.

## About the colors

The Rico numbers and their Anchor and DMC equivalents come from Rico Design's printed Sticktwist color card (No. 2011.001–296). Rico does not publish screen colors, so each swatch uses the screen color of its DMC equivalent, taken from the open [`sharlagelfand/dmc`](https://github.com/sharlagelfand/dmc) dataset, which in turn builds on [`adrianj/CrossStitchCreator`](https://github.com/adrianj/CrossStitchCreator).

- Eight Rico colors list no DMC match on the card (097, 100, 151, 173, 199, 217, 218, 263). Their screen colors are estimated from neighbouring colors and marked with `≈`.
- The metallic threads (921, 922, 941, 942, 943) use approximate colors.
- Screen colors are approximations. Compare with the physical color card before buying a lot of thread.
- Skein counts are estimates for 6-strand skeins of 8 m with 25 % extra for waste.

## Disclaimer

This is an independent hobby project. It is not affiliated with or endorsed by Rico Design GmbH & Co. KG, DMC or Coats (Anchor). Rico Design, DMC and Anchor are trademarks of their respective owners and are used only to identify compatible thread colors.
