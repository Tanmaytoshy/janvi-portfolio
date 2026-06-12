# Jaanvi Toshniwal — Portfolio (Pastel Collage)

## Files
- `index.html` — the entire site (HTML + CSS + JS, single file, no build step)
- `assets/` — empty folder, ready for local copies of images/videos

## Run it
Open `index.html` in any browser. To host, upload the folder to any static host of your choice.

## Important: media is hotlinked
All work images, reels, and the profile photo currently load from:
`https://jaanvi-toshniwal-creative-hub.lovable.app/lovable-uploads/...`

If that site ever goes down, the media breaks. To make it self-contained:
1. Save each image/video from the old site into `assets/`
2. In `index.html`, find-and-replace
   `https://jaanvi-toshniwal-creative-hub.lovable.app/lovable-uploads/` → `assets/`

## Before publishing
- Hook up the two contact buttons (search for `drop me a line` and `find me on LinkedIn` and add real `href` links)
- Optional: edit chapter text in the "journey" section, add/remove polaroids in the work grids (each card is a `<div class="polaroid">` block)

## Structure
- Ticker + nav
- Hero (profile polaroid + floating stickers)
- The Jaanvi Storyline — 8-chapter timeline
- Pinned to the Wall — 10 featured pieces
- Carousel Diaries — 4 swipeable carousels
- The Reel Deal — 5 video reels
- Toolbox + skill cloud
- Brag corner, contact, footer
