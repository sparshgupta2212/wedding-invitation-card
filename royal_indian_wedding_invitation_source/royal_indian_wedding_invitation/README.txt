ROYAL INDIAN WEDDING INVITATION WEBSITE — FREE SOURCE CODE

This is a mobile-first, single-page Indian wedding invitation website inspired by the uploaded example: cover, countdown, multiple ceremony sections, family section, venue/map, wishes and RSVP buttons. It uses plain HTML/CSS/JavaScript, with no framework or build step.

FILES
- index.html: all source code in one file.

CUSTOMIZE
1. Open index.html in VS Code or Notepad.
2. Near the bottom, find `const WEDDING = { ... }` and change bride, groom, dateISO, dateLabel, venueName, venueAddress, mapsQuery, and hostWhatsApp.
3. Edit the event cards in the HTML for the actual dates/times/venues (search for `Haldi`, `Mehendi`, `Sangeet`, `Wedding`, `Reception`).
4. Set hostWhatsApp to the family's WhatsApp number including country code, digits only (example format: 919876543210). Without a number, WhatsApp opens with the message text and lets the sender choose a recipient.
5. Optional music: add an MP3 you have permission to use next to index.html, then set `const MUSIC_FILE = "wedding-music.mp3";`.
6. Replace the decorative emoji in the ceremony artwork with couple/ceremony photos if you want. For a simple photo, replace the content inside an `.event-art` div with `<img src="your-photo.jpg" alt="Haldi ceremony">` and add `.event-art img{width:100%;height:100%;object-fit:cover}` to CSS.

FREE LOCAL PREVIEW
Double-click index.html to open it in Chrome.

FREE PUBLISHING (public share link)
Option A — GitHub Pages:
1. Sign in to GitHub and create a PUBLIC repository.
2. Upload index.html to the repository root.
3. Open Settings > Pages. Choose Deploy from a branch, select `main` and `/(root)`, then Save.
4. Wait for GitHub to publish the page; share the resulting `https://YOURNAME.github.io/REPOSITORY/` link.

Option B — Netlify Drop:
1. Visit https://app.netlify.com/drop.
2. Drop the folder containing index.html (sign in if prompted).
3. Share the generated netlify.app link. Free-plan limits and terms can change.

IMPORTANT LIMITATIONS
- The template is static and free; no paid theme, custom domain, database, or backend is required.
- The RSVP/wishes buttons open WhatsApp with a prefilled message; they do not store responses in a database themselves.
- Hosting providers may change free-plan limits. A custom domain is optional and usually costs extra.
- Replace all sample names, dates, venue and contact details before sharing publicly.
