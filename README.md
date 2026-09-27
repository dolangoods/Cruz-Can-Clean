# Cruz Can Clean

One-page website for Cruz's trash and recycling can cleaning business in Willowsford's Grove (Aldie, VA).

- **Schedule:** Saturday mornings, the day after Friday trash and recycling pickup
- **Service area:** Willowsford, The Grove only
- **Price:** $15 per clean
- **Payment:** cash or Venmo @NVD-17
- **Contact:** (703) 408-0701
- **Cruz brings:** power washer, soap, degreaser, extension cord
- **Homeowner provides:** access to an outdoor hose spigot and power outlet

## Files

- `index.html` is the whole site: HTML, CSS, and JS in one file. Fonts load from Google Fonts; nothing else is external.

## To do

- **Photos:** the "Before and after" section uses cartoon illustrations (inline SVG). To swap in real photos, replace a `<div class="ph toon">` with an `<img>` (before/after panels are 3:4, "on the job" shots are 16:9).
- **Booking:** the sign-up section embeds Cal.com (`cal.com/cruz-can-clean/cleaning`) for the four Saturday slots. Availability, slot count and booking questions are managed in the Cal.com dashboard, not in this repo.
- **Hosting:** works as-is on GitHub Pages (Settings → Pages → deploy from `main`).
