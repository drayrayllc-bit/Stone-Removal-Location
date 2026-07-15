LIVE PROGRESS MAP INSTALLATION

Files to upload beside your current website index.html:
1. index_live_progress.html (rename to index.html)
2. stone-overlay.json
3. progress-map-page-1.webp
4. progress-map-page-2.webp

Google Apps Script:
1. Replace your Apps Script with APP_SCRIPT_LIVE_PROGRESS.txt
2. Deploy > Manage deployments > Edit > New version > Deploy
3. Keep the same /exec URL.

How it works:
- The Progress Map tab displays Page 1 (North/East) or Page 2 (South/West).
- It polls Google Sheets every 30 seconds.
- Removed stones are red at 50% opacity.
- Reinstalled stones are green at 50% opacity.
- To Be Removed stays clear.
- Saving a status in Admin mode also triggers a near-immediate refresh.
- No PDF is generated or downloaded.

The progress-map-base.pdf is included only as an archive/reference and is not required by the website.
