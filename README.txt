TIZI AIR - website
==================

To view: open index.html in Chrome, Edge, Firefox or Safari.
Everything is inside this folder (photos, video, fonts, code), so it works offline.
Keep the "assets" folder next to index.html.

To publish online: upload the whole folder (index.html + assets) to any web host,
for example Netlify Drop (drag the folder onto app.netlify.com/drop), GitHub Pages or your hosting's file manager.

Before going live:
- Booking email: in index.html search for  BOOKING_EMAIL  and replace book@tizi-air.example with your address
  (also change the same address in the footer).
- Check the wording of the day timeline, safety and FAQ.

Folder:
  index.html            the page
  assets/img            your photos (WebP)
  assets/video/hero.mp4 hero video (1920 px, 8 s loop, no sound)
  assets/fonts          Big Shoulders Display + Schibsted Grotesk (SIL Open Font License)
  assets/js             GSAP (animation), scenes.js (3D: three.js, MIT licence)

Speed and SEO update (10 Nov 2026)
----------------------------------
The page looks and reads exactly as before. Changes are behind the scenes:
- Hero video compressed: hero.mp4 (desktop, 320 KB) and hero-720.mp4 (phones, 87 KB) instead of 2.4 MB.
- Phones get lighter copies of each photo (the *-480.webp files).
- The 3D code (scenes.js) loads only when it is needed, so the page opens faster.
- New SEO head: title, description, canonical, share image, and structured data for Google
  (business, the three flights with prices, the day itinerary, and the FAQ).
- New files: sitemap.xml, robots.txt, llms.txt (facts for AI assistants), site.webmanifest,
  .htaccess (HTTPS, compression, caching on Apache/LiteSpeed hosting), app icons.

Before going live, also replace  tizi-air.com  with your real domain in index.html, sitemap.xml,
robots.txt, llms.txt and .htaccess, then submit sitemap.xml in Google Search Console.
