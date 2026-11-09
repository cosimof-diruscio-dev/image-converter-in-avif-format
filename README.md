# 🌐 AVIF Image Converter (Node.js CLI)

A CLI script that automates a tedious task: batch-converting images to a modern, lightweight web format.

## What it does
- Scans a folder for `.jpg`, `.png`, `.gif`, `.webp` files
- Converts them to AVIF at quality 70%
- Saves output to a separate folder
- Skips already-converted files on re-run (checks file existence first) — no redundant processing

## Impact
Reduces average asset weight by 50%, with a direct effect on Core Web Vitals and page load performance.

## Tech Stack
- JavaScript — conversion logic
- Node.js — file system operations, `sharp` and `glob` packages

## Usage
```bash
git clone https://github.com/greenexplorerdev/image-converter-in-avif-format.git
cd image-converter-in-avif-format
npm install sharp glob
```
1. Create a folder named `immagini` and add your images.
2. Run: `node index.js`
3. Converted files appear in `immagini/convertite`.

## Screenshot
Initial weight

<img width="812" height="309" alt="peso_immagini_non_convertite" src="https://github.com/user-attachments/assets/888b8386-3426-4111-94fd-4c13344207e3" />

final weight

<img width="707" height="333" alt="peso_immagini_convertite" src="https://github.com/user-attachments/assets/e44893bd-e2ed-4c64-9c48-f0f44ed902fd" />

## Contact
Open to feedback and collaboration opportunities.
[LinkedIn](https://www.linkedin.com/in/cosimo-francesco-di-ruscio) · diruscio.cosimo@gmail.com
