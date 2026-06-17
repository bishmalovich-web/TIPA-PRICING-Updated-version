# TIPA Film Pricing App

Files in this package:

- `index.html` — the pricing app generated from `Updated Model_16.06.2026_3 copilot.xlsx`.
- `tipa-pricing-qr.png` — QR code for the GitHub Pages URL used before: https://bishmalovich-web.github.io/tipa-pricing/
- `README.md` — this guide.

## What the app includes

- Film Type dropdown from the Excel helper/data.
- Width, thickness, density, weight, length, hourly rate, shipping destination, margin.
- Input Mode from Excel rows 20-21: `By Weight` or `By Length`.
- Sell Price in EUR, matching the Excel logic from row 16.
- Sell Price in USD, using exchange rate `1.16` from the Excel helper sheet.
- Mobile-friendly design and QR code.

## Upload to GitHub Pages

1. Open your GitHub repository, for example `tipa-pricing`.
2. Upload `index.html`, `tipa-pricing-qr.png`, and this `README.md` to the root folder.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select **Branch: main** and **Folder: / root**.
6. Save.
7. Open the GitHub Pages link.
8. Scan the QR code from your phone.

## Important

GitHub Pages is static. If the Excel file changes, regenerate and upload a new `index.html` so the app matches the updated Excel.
