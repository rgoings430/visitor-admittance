Visitor Admittance v1.8 - FREE ZXING-WASM

Scanner engine:
- zxing-wasm 3.1.5
- ZXing-C++ compiled to WebAssembly
- Free/open-source
- PDF417 supported
- No Dynamsoft license required

Architecture:
Custom Web Front End -> later Google Sheet -> AppSheet admin/backend

GitHub Pages update:
1. Open your visitor-admittance repository.
2. Replace the existing index.html with this index.html.
3. Commit changes.
4. Wait for GitHub Pages to redeploy.
5. On iPhone Safari, refresh:
   https://rgoings430.github.io/visitor-admittance/
6. Tap Scan ID Barcode.
7. Allow camera access.
8. Use rear camera and fill the white scan box with the PDF417 barcode.

The scanner alternates between a tight barcode-region crop and a full camera frame.
