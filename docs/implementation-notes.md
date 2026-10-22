## Runtime notes
The standalone recreation is in `/home/ian/lifetime-design-recreation` to avoid overwriting `/home/ian/liftco-website`, which contains a separate, already modified Liftco website. Use `npm install` then `npm run dev` in the new directory. This environment had Next 16/React 19 available in the existing Liftco directory; a fresh `npm install` in the isolated folder timed out, so the successful production build used those existing local modules. No lockfile could be generated here.

## Verification / limitations
- `npm run build` completed successfully with TypeScript and static generation: `/`, `/our-expertise`, `/about-us`, `/awards-articles`, `/contact`, and dynamic `/articles/[slug]`.
- Production server returned HTTP 200 for all five primary routes and `/articles/ide-desain-rooftop`.
- Browser-based local screenshot comparison could not be completed: the browser daemon timed out (Chromium missing/unavailable). Reference screenshots were captured visually for M Design homepage and Lifetime Design homepage; no claim of pixel parity.
- M reference pages were inspected via rendered desktop/accessibility snapshots. Lifetime official home/about/portfolio/blog/interior service/architecture service/Estate pages were checked; `/proyek/` navigation timed out. Mobile reference and hover/slide timings were not captured.
- Mobile menu opens/closes with click and nav selections; image arrows are currently decorative and do not change slides. Article pages are concise local excerpts linking out to the verified official blog, not copied full articles.
- Local asset filenames use numbered generic labels rather than semantic filenames. The site uses authentic official-hosted Lifetime Design photos but image/project-to-caption identity was not verified. The temporary logo is a text monogram, not an identified official logo asset.
- Colors and font selections are approximate, since browser computed style extraction was unavailable. Source website content/asset copyright permission should be confirmed before public deployment.
- The WhatsApp handoff uses `0815 1148 2222`, captured on Lifetime Design's official interior service page's contact details; it is labeled as an Interior contact channel, not asserted as the corporate central contact.
- No awards are fabricated; the awards section is replaced by blog content. No email or phone number is invented.
