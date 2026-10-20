# PSI — provisional web painting app

**Open the app: https://mishiki.github.io/psi/**

PSI is an independently modified version of [Klecks](https://github.com/bitbof/klecks), with raster and vector editing, layer masks, and experimental SAI2 import/export powered by [sai2-parser](https://github.com/mishiki/sai2-parser).

This is a provisional release. PSI is not affiliated with or endorsed by SYSTEMAX or PaintTool SAI. Keep original artwork files when trying SAI2 round trips; compatibility is still being developed.

## Use

Open the site in a current desktop browser, then choose File → Open. Editing and file conversion run locally in your browser. Save downloads the result to your computer. Imgur upload is disabled in this standalone deployment. Browser storage, where available, is local to your browser and is not cloud backup.

This repository contains the deployable static release, including WebAssembly, rather than the development checkout. No private artwork fixtures, diagnostics, or personal keybinding files are included.

## Licenses and credits

Klecks: Copyright (c) 2026 bitbof (bitbof.com), MIT License. The full original license is preserved in [LICENSE](LICENSE).

SAI2 support: [sai2-parser](https://github.com/mishiki/sai2-parser), MIT License.

Full third-party copyright notices and license texts for JavaScript, WebAssembly dependencies, fonts, and bundled assets are in [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt). The application also retains its original library and font license viewer.

Deployment: GitHub Pages from the root of the `main` branch. `.nojekyll` preserves the prebuilt static assets.
