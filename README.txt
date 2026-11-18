MARMOT MAINTENANCE TALLY - IPHONE APP (UPDATED)
================================================

UPLOAD TO EXISTING GITHUB REPOSITORY
1. Extract the ZIP file.
2. Drag its 7 files into the ROOT of the SAME GitHub repository as the existing app.
3. The filenames are identical to the original upload: index.html, README.txt,
   sw.js, manifest.webmanifest, apple-touch-icon.png, icon-192.png and icon-512.png.
4. Choose to replace/commit the existing files (do not create a new subfolder).
5. After GitHub Pages deploys, reopen the same app URL on your iPhone.
6. If your Home Screen app is showing an old cached view, close it and reopen;
   if necessary open the website in Safari online and reload to update cache.

KEY FEATURES
- Enter phase, walk and inspection date.
- Tap to count any 1.5-m-long piece of rolled curb, monowalk or separate walk.
- Main tally: 1.5 m and 2.0 m separate sidewalk, plus the original curb/mono.
- Other structures: 2.5 m and 3.0 m separate sidewalk, plus other existing items.
- For separate walk, each piece's area = walk width x 1.5 m.
- Volume = area x pull: 0.100 m3/m2 at 100 mm or 0.125 m3/m2 at 125 mm.
- Flag / Infill: type each rough m2 estimate, then press Enter / Done or tap
  '+ Add'. Each entry is stored separately and added to the running total.
- Undo latest flag entry, remove earlier sections, and see all section entries.
- Inspection totals, CSV export, print/PDF and JSON backup still work.
- Existing saved inspection records are preserved under the same local storage
  keys. Any previous Separate Sidewalk m2 total is preserved as a prior value.

EXAMPLES at 125 mm thickness
  One 1.5 m wide separate walk piece:
     1.5 m x 1.5 m = 2.25 m2; x 0.125 = 0.28125 m3
  One 2.0 m wide separate walk piece:
     2.0 m x 1.5 m = 3.0 m2; x 0.125 = 0.375 m3
  Flag sections entered as 2.5 m2, 4.0 m2 and 1.5 m2:
     total = 8.0 m2; x 0.125 = 1.0 m3

The app is a standalone GitHub Pages web app. Data is saved on your device, not
on GitHub. Export a JSON backup periodically; deleting local website data
can erase inspections. Estimates should be checked against measured quantities.
