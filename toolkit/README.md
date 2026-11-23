# Aristotle House, Route 02 Heatmap: toolkit (24 November 2026)

## 1. Heatmap tool (AH_Heatmap_Tool.html)
Open in Chrome. Runs offline, nothing is uploaded.
1. Open image or icon (or drop it on the window).
2. Pick a preset:
   - Work · Lyceum: the main look for event and people photography.
   - Work · isotherm: stepped bands with contour lines.
   - House · Ultra: calm violet to salmon, for the House's own channels.
   - Day · Lyceum: for white or bone grounds.
   - Icon · heat: for line icons (black on transparent PNG).
3. For people: in Photoshop use Select > Subject, fill white on black, export a PNG at the same size, then "Add subject mask". People read warm, the room reads cool.
4. Export PNG, full size.

## 2. Photoshop colour lookups (.cube)
AH_lyceum, AH_lyceum_ring, AH_ultra, AH_lyceum_day.
Soften the photo first (Gaussian Blur 4 to 8 px at 2000 px wide), add a Color Lookup adjustment layer and load the .cube, then add Noise 3 to 5%.
Lyceum stops: 0 #07060D · 18 #1B1464 · 36 #4B2EF5 · 52 #C7B8FF · 66 #FF4FB4 · 78 #FF2E7E · 88 #FF7A5C · 100 #FFEFC2

## 3. Line icons (icons/)
Draw on AH_icon_grid_template.svg: 24 grid, 2 unit margin, 1.6 stroke, round caps and joins, black on transparent.
Export PNG 600 px and run through the tool with the "Icon · heat" preset.

## 4. Marks (marks/)
The gaze icon (for dark and light grounds) and the seal (the A, and the A in a square), in bone and ink.

Colours: Ink #0B0A0F · Charcoal #2E2E31 · Bone #F2EFE8 · Lyceum violet #4B2EF5 · Lilac #C7B8FF · Signal pink #FF4FB4
Type: Zalando Sans Expanded (logo and headlines) · Aktiv Grotesk (text and readouts)
