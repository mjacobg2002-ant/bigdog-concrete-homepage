# Big Dog Concrete Construction — Homepage Redesign (Concept)

A premium homepage concept for **Big Dog Concrete Construction**, a family-owned concrete,
asphalt, and masonry contractor in **Manassas, VA**, serving Northern Virginia.

This is a **homepage shell/concept for client presentation** — not the full production site.

## Stack

Single static `index.html` — no build step, no dependencies. Open the file or serve the folder.
Fonts load from Google Fonts (Anton + Inter); everything else is local.

## What's authentic

Pulled from the client's real site (`https://bigdogconcreteconstruction.com/`):

- **Logo** — the real Big Dog logo (`images/logo.jpg`), used as-is.
- **Fleet photo** — the company's real branded dump truck (`images/fleet-truck.jpg`), shown in the
  "who we are" section.
- **Copy & facts** — family owned & operated; the three pillars (Honest & Personal Service,
  Competitive Pricing, Quality Workmanship); the full concrete/asphalt/masonry service lists;
  dumpster delivery & fire pit installation; the real commercial project references
  (First Service Residential & Ashland Conservancy, Hermitage Hills Apartments, Magna Construction,
  Oakwood Apartments); phone `(703) 618-2477`; email `service@bigdogconcreteconstruction.com`;
  `7703 Well St., Manassas, VA 20111`; hours Mon–Fri 9am–5pm, Sat–Sun closed.

Nothing was fabricated. There are **no testimonials, years-in-business, or licensed/insured claims**
on the source site, so none appear here.

## Stock imagery (client-approved practice)

Big Dog's own site has almost no project photography, so the trade/scene images use free stock
photography from Pexels (license: free to use, no attribution required). Alt text does not claim
these are specific Big Dog projects:

- `hero-concrete-crew.jpg` — Pexels 37121405
- `concrete-driveway.jpg` — Pexels 8134845
- `asphalt-paving.jpg` — Pexels 36861831
- `masonry-brick.jpg` — Pexels 19688828
- `commercial-paving.jpg` — Pexels 34053335
- `process-pour.jpg` — Pexels 33405139
- `process-screed.jpg` — Pexels 37121398
- `process-finish.jpg` — Pexels 4134382

The **logo** and **fleet truck** are the company's own.

## Brand & design

Built around the real logo: **bold black + safety yellow + white**, rugged/industrial. Anton
(display) + Inter (body). Solid white sticky header, full-bleed hero, three trade "division" cards,
a concrete-services detail grid, a commercial/VDOT section with real client references, a process
strip, a service-area block, and a low-friction estimate form. Semantic HTML, one H1, keyboard
navigable, visible focus states, reduced-motion support, LocalBusiness JSON-LD, lazy-loaded imagery.

## Deploy (GitHub Pages)

Settings → Pages → Deploy from a branch → `main` / root → Save. Publishes at
`https://<user>.github.io/<repo>/`.

## Note

The estimate form is a front-end concept (no backend); on submit it confirms and points to the
phone number. Wire it to a form handler before going live.
