# VAT‑Scan — AdSense Starter

**Deploy**: drag-and-drop this folder to Vercel or Netlify.  
**Replace**: set your AdSense publisher ID in:  
- `index.html` (query param `client=ca-pub-REPLACE_WITH_YOUR_ID` and `data-ad-client`)  
- `ads.txt` (pub-XXXXXXXXXXXX)  

Flow:
1) Apply to AdSense and add site https://vat-scan.com.
2) When approved, replace publisher ID in the two files above.
3) Ensure `ads.txt` is live at https://vat-scan.com/ads.txt.
4) Keep Privacy/Terms linked in header.
5) Consent banner controls ad loading (Consent Mode v2).

Updated: 2025-11-01
