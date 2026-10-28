TRAILHAVEN — FREE SINGLE-PAGE HTML EDITION
Plain HTML, CSS and vanilla JavaScript. No build or package install.

OPEN AND RUN
Keep index.html and the complete assets folder together. Open index.html
for a quick preview. For dependable font/clipboard behaviour use a local
static server, for example if Python is installed:
    python -m http.server 8080
Visit http://localhost:8080/ and stop the server with Ctrl+C.
No React, Vite, npm, database, account or API key is required. All runtime
fonts, images, JavaScript and styles are bundled locally.

EDIT
- index.html: visible content, metadata, route rows, native day plans, form,
  headings, photo descriptions and author credit.
- assets/css/trailhaven.css: palette, typography, responsive spacing/layout.
- assets/js/trailhaven.js: filtering, itinerary enhancement and unsent text.
- assets/img/: three local landscape photos, original mark and route map.
- Each .trip-row has data-trip/data-duration/data-pace values. Its h3,
  image and .itinerary-body are the source of the detailed dialog, so edit
  those once. Preserve unique route IDs and matching in-page links.
- Native duration radios and a gentle-pace checkbox filter the collection.
  Day + gentle shows Lakepath. Weekend + gentle gives an honest empty state.
- View itinerary opens a native dialog when supported. Enquire about this
  trip fills the selected-trip name and hidden form field. The selected
  trip carries into the draft. It remains selected if list filters change.
- With JavaScript disabled, all trips and native inline day-plan details
  remain available. Local enquiry generation is disabled with a message.
- There is no date/time/select field. Broad season/group radio choices are
  preferences, never real departure dates or availability.

UPLOAD AT A DOMAIN ROOT
Upload index.html plus assets/ to your static host's public root (often
public_html). Keep filenames/case/folders unchanged and serve via HTTPS.
No build, rewrite, SPA fallback or server runtime is needed. Preserve the
LICENSE/notices/licenses with source and any redistributable package.
No private config, credentials or environment files belong in this package.

UPLOAD IN A SUBFOLDER
Upload the full directory to /trailhaven/ or another chosen folder. Visit
https://your-domain.example/trailhaven/ with the trailing slash. All runtime
assets are relative; do not prepend a base path or add a <base> tag.
Check direct loading, refreshing and in-page navigation after upload.

CUSTOM DOMAIN
Use the chosen host's current DNS and HTTPS instructions. This package
cannot connect a domain, configure DNS or provision a hosting service.
There are no remote runtime requests, analytics, cookies, payment systems,
form providers or external account integrations configured.

HONEST LIMITS
- Every itinerary/name/distance is fictional sample content. No real tour,
  price, availability, accommodation, guide, equipment, permit or booking.
  Replace with verified business content before using this for a business.
- Photographs illustrate the mood; they do not establish actual destinations.
  The map is a schematic original, not navigation or verified route data.
- Pace/distance descriptions compare fictional concepts, not personal
  suitability or safety. Discuss current conditions and requirements with
  a qualified local organiser before any real trip.
- The adult enquiry form only creates an UNSENT local text draft. Nothing
  is sent, booked or stored by this page. No passport, health, child or
  payment data should be entered. Browser autofill may independently retain
  contact information; this site adds no persistence.
- After changing preferences/selected trip, Prepare my enquiry again to
  update the draft. Copy uses the Clipboard API when allowed and text
  selection as fallback. Download generates a local text file. These are
  actions on your device, not evidence of submission.
- Native details provide a no-JS fallback. Modern browser dialog, inert,
  animation and ResizeObserver support improve progressive enhancements.
  Touch/keyboard scrolling remains native; desktop normal motion uses Lenis
  through one shared animation clock. Reduced motion removes animation.
- Parent served browser acceptance remains separately recorded in docs/QA.md.

LICENCES
Original template MIT: LICENSE. Shared mechanics Nookwell/Taskline MIT,
including Themesberg; Lenis MIT; Fraunces/Manrope SIL OFL 1.1. Full grants
in licenses/. Photo origins/Unsplash terms: THIRD_PARTY_NOTICES.txt and
licenses/photo-sources.json. Photos may not be sold as standalone stock.
The footer links only the bold Usman Khair Din author name to
https://www.usmankhairdin.com/.
