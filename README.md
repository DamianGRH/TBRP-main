# Leonida Network — GitHub Pages starter

Open index.html directly to try the prototype. No installation, API key, build, or external dependencies are required.

## Publish on GitHub Pages
1. Create a GitHub repository and upload index.html to its root.
2. Open repository Settings → Pages.
3. Select Deploy from a branch, select main and /(root), then Save.
4. GitHub displays your Pages address when deployment finishes.

## Included
- Responsive dark and pink community hub inspired by the supplied reference.
- Searchable and filterable content library with detail dialogs.
- Illustrative SVG map with zoom, pointer panning, category filters, location search, keyboard-selectable markers, and discoveries saved in localStorage.
- No fabricated game news, mission details, vehicle statistics, or real map coordinates.

## Before a public launch
Replace the community setup dialog with your actual Discord link. Add verified articles, publication dates, source links, vehicle entries, and spoiler-aware mission guides. Replace the concept SVG map and fictional demonstration coordinates with properly licensed, verified map data. Supply original or licensed artwork; the current artwork is a decorative SVG skyline, not GTA VI imagery.

The map is a functional UI prototype, not a complete GTA VI map. News cards link to sourced articles; library cards remain editorial placeholders. Browser progress is local to each browser/device; private mode or clearing storage can remove it. No accounts, submissions, automatic news refresh, or cross-device sync are connected. Those need a separate backend, such as Supabase or Firebase, or a publishing workflow such as GitHub Actions.

## Editing
The single index.html contains styles, markup, and JavaScript. Edit the news and library arrays for content; edit points and types for demonstration markers. Content is inserted using textContent. For a growing catalogue, move these arrays into JSON files and serve the site through HTTP.

## Verification
JavaScript syntax and HTML structure checked locally. Browser visual and interaction QA still required before production.

## CG Scripts inspired scrolling update
Full-height gradient hero, native smooth anchor scrolling, pinned opening-curtain reveal, scroll progress bar, moving announcement band, section entrance effects, card hover lifts, active navigation, and back-to-top control. The motion button pauses effects and remembers the choice; system reduced-motion preferences disable them automatically. No wheel hijacking or scroll-blocking library.


## GTA VI newsroom update — 20 October 2026

The newsroom now includes two official Rockstar Newswire announcements and an explicitly labelled historical GameSpot report. Each card displays its publisher, publication date, an original summary, and an outbound article link. The current selection was checked on 20 October 2026. The latest Newswire and official GTA VI site buttons lead directly to Rockstar for newer information.

This is the safe client-side option for static hosting: the curated list is embedded in index.html and rendered with textContent. There are no API keys, credentials, runtime feed requests, CORS proxies, new dependencies, or Actions permissions. It works both on GitHub Pages and when index.html is opened locally. Links opened in new tabs use noopener noreferrer. A no-JavaScript Newswire link is provided.

### Maintaining the news

Edit the news object array in index.html. Each entry has kind, title, summary, source, date (YYYY-MM-DD publication date), and url (direct HTTPS publisher article). Keep summaries original and brief; distinguish official announcements, reporting, and historical coverage. Review against the publisher, sort newest first, and update the visible “checked” date only after reviewing the selection. This is a curated selection, not an automatically refreshed or exhaustive feed. No copyrighted article text or publisher images are bundled.

### Publishing these changes

Replace index.html and README.md in DamianGRH/TBRP on a branch and review the changes before merging. The existing GitHub Pages branch deployment needs no build changes. No deployment or GitHub commit was performed while preparing this ZIP because the connected GitHub repository tools were unavailable.


## Official media

The Official media section includes an on-demand YouTube privacy-enhanced embed of Trailer 2 from Rockstar's verified channel. No player connection is made until Load is selected; it does not autoplay. An ordinary YouTube link remains available if embedding fails or JavaScript is disabled. Browser/file-origin or publisher restrictions can affect playback; verify on the actual Pages URL.

Screenshot, artwork and video cards link to Rockstar's official galleries, with attribution. Direct Rockstar asset loading was not verified, so no unreliable image or MP4 hotlinks are shipped. Decorative gradients remain clearly identified. No Rockstar media files are copied into this bundle. The player and galleries need internet access.
