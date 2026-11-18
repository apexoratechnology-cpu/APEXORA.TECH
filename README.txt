APEXORA.TECH website
=====================
Open index.html in a browser to view it. To put it online, upload this whole folder to any static host (Netlify, GitHub Pages, Vercel, or your own hosting).

Edit your content in js/app.js (top of the file):
  CONFIG     - email, phone numbers, Instagram, location
  OFFICIALS  - names, designations, degrees, Instagram, email, bio. g:'m' = first row, g:'f' = second row. Photos: assets/team/team-01..09.jpg in the same order.
  REVIEWS    - add genuine customer reviews: {name, stars, text, photo}
  STATS      - Highlights counters
  SW / CV / D3 / LS - service names and prices
  GAL        - Highlights gallery photos and project links

Images are in assets/. Replace a file with the same name to change a photo.
Colours are the variables at the top of css/style.css.
Intro videos: assets/intro-landscape.mp4 (desktop 16:9) and assets/intro-portrait.mp4 (mobile 9:16). They play at every visit (with sound when the browser allows it, otherwise muted), then the home page opens.

ZENVIX (Business Associate)
  Opens at index.html#zenvix. Edit the ZX block at the bottom of js/app.js.
  Logo: assets/zenvix/zenvix-logo.jpg (set in ZX.logo). Service photos: ZP list in js/app.js (assets/zenvix/).
  Gallery: put photos in assets/zenvix/ and add  {src:'assets/zenvix/photo-1.jpg',title:'Name'}  lines to ZX.gallery.
Intro videos: assets/intro-landscape.mp4 (desktop 16:9) and assets/intro-portrait.mp4 (mobile 9:16).

SERVICE NUMBERING (added)
  Software Projects: 1-12 (SW) + 13-20 (SW2) + 21-40 (SW3) in js/app.js
  Canva Designs:     1-30 (CV)  + 31-60 (CV2 block in js/app.js)
  Photos: assets/canva/canva-01..60.jpg (one per Canva service number); extra-XX.jpg = second photo for that service number (XI list in js/app.js).
