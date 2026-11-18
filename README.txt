MARMOT MAINTENANCE TALLY - IPHONE APP
====================================

WHAT IT DOES
- Enter Phase, Walk, and Date of Inspection.
- Tap + to count each 1.5 metre replacement piece; use - to correct mistakes.
- Enter rough square metres for Separate Sidewalk and Flag / Median Infill.
- Select 125 mm (default) or 100 mm slab thickness. Concrete pulls change accordingly.
- Optional extra structures: 500 mm rolled curb, 1.1 m rolled mono, 600 mm drainage swale, and commercial walk/fill.
- Automatically shows number of pieces, linear metres, rough square metres, and estimated total cubic metres.
- Records autosave on the device; multiple separate inspections are supported.
- Download an Excel-compatible CSV, print/save a PDF, share a text summary, or back up inspections as JSON.

INSTALL ON YOUR IPHONE USING GITHUB PAGES
1. Extract this ZIP file. Keep all the files together.
2. Create a GitHub repository (or use a dedicated repo for this app).
3. Upload ALL the files in this folder to the repository root. The homepage must be named index.html.
4. In your GitHub repo go to Settings > Pages > Build and deployment.
5. Choose Deploy from a branch > main > / (root) > Save.
6. Open your published GitHub Pages URL in Safari on your iPhone.
7. Tap Safari's Share icon > Add to Home Screen > Add.
8. Open the new Maintenance Tally icon from your Home Screen.

NOTES
- This app requires no login, server, database, or API. No inspection data is sent to GitHub or to Marmot.
- GitHub Pages serves only the app's code, icons and cached support files.
- Inspection data is saved in this browser/Home Screen app's LOCAL storage. It does not sync between devices.
- iPhone Safari and the installed Home Screen app may maintain separate storage; use the JSON backup for migration.
- Use Inspections > Export backup regularly; deleting Safari app/site data can erase local records.
- The app's offline ability begins after it is first successfully loaded online and cached.
- Opening index.html as a file directly may not support Home Screen install or persistent local storage.
- CSV files open in Microsoft Excel and can be saved as regular .xlsx files if desired.
- To make a PDF: Totals > Print / Save PDF, then in iOS print preview use Share > Save to Files.

PULL SOURCES: Maint Pull.xls (Sheet1, rows 4-11)
------------------------------------------------
  250 Rolled Curb:                 0.115 m3/LM (constant)
  500 Rolled Curb:                 0.141 m3/LM (constant)
  1.1 Rolled Mono (100 / 125):    0.214 / 0.2415 m3/LM
  1.5 Rolled Mono (100 / 125):    0.254 / 0.2915 m3/LM
  2.0 Rolled Mono (100 / 125):    0.304 / 0.354 m3/LM
  Separate Sidewalk/Flag/Infill:  0.100 / 0.125 m3/m2
  Commercial Walk / Fill:        0.150 m3/m2 (constant)
  600 mm Drainage Swale:          0.145 m3/LM (constant)

All counted pieces are estimated at 1.5 LM, including curb and swale.
The 100 / 125 mm selector only affects structures with two rates in the supplied file.
The two separate area boxes use the SAME pull from the combined spreadsheet row.

This is a preliminary scope estimate, not a field measurement or concrete order.
