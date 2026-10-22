# Reference audit — Lifetime Design recreation

## Scope and evidence
Reviewed live desktop-rendered pages and accessibility snapshots on 2026-10-22: M Design Group `/`, `/our-expertise/`, `/about-us/`, `/awards-articles/`, `/contact/`; Lifetime Design `/`, `/tentang-kami/`, `/portfolio/`, `/blog/`, `/jasa-desain-interior/`, `/jasa-arsitek-rumah/`, `/lifetime-design-estate/`. Estate page successfully returned content; `/proyek/` timed out. No reliable tablet/mobile reference captures or hover inspection were available; responsive behavior below is a functional approximation, not claimed measured parity.

## Reference design measurements (homepage screenshot, browser viewport approximately 1265×3440; measured visually from rendered screenshot)
- M Design header: white, about 70 px high; compact left logo; horizontal navigation and dark brown contact button.
- Hero: full viewport width, about 636 px high in screenshot; image-backed, left-aligned white uppercase sans-serif heading, supporting copy, rectangular CTA; circular previous/next controls; lower image caption and centered slide markers.
- Intro: white with narrow horizontal rule, centered high-contrast editorial serif heading and gray centered support; three equal image cards with dark lower gradient; content width about 1200 px and 30 px gutters.
- About: full-width dark brown panel, image carousel left / large white copy right.
- Insights: centered serif display title, subtitle, two-column article blocks in warm off-white, rust-red categories and links.
- Closing CTA: large gray field with centered uppercase white type and overlapping brown button; pale warm footer with horizontal five-link nav, address/contact area and thin dividers.
- Expertise snapshot: centered title and subtitle then four prominent image-led brand/service rows/cards.
- About snapshot: group philosophy, three brand sections and a history-like visual. Reference text-only snapshot did not expose exact image/timeline arrangement, so exact details remain unknown.
- Articles snapshot: AWARDS heading and award gallery, then insights list and featured articles. Do not transfer reference awards; this implementation substitutes verified Lifetime Design blog posts.
- Contact snapshot: multiple brand offices and maps above an inquiry form. This recreation only publishes the main office address verified on Lifetime Design homepage; no fabricated phone/email/social handles.

## Lifetime Design content map
- Identity/home: official name, headline “Mengubah Ruang dengan Desain Terbaik yang Elegan”, one-stop interior/architecture/renovation description.
- Brands: Lifetime Design Interior (official interior service URL), Lifetime Design Arsitektur (official architect URL), Lifetime Design Furniture (main official site; no standalone verified address discovered).
- History: beginning in 2007 from Lifetime Design about-page metadata/user-provided brief; no invented intermediate milestones.
- Contact: address from official homepage: Jl. Pangeran Antasari No.70, RW.8, Cilandak Barat, Kec. Cilandak, Kota Jakarta Selatan, DKI Jakarta 12430.
- Articles: four titles/dates captured from official blog list; linked locally to article pages that provide brief summaries and outbound official blog link (full source article body not extracted).
- Projects: Lifetime Design gallery assets collected, but source pages did not reliably identify image-to-project title mappings; portfolio labels are broad service categories rather than falsely asserting specific project names.

## Tokens / typography
- Lifetime Design visible accents are warm rust/brown on white and warm cream surfaces. CSS colors are provisional visual sampling: `#493832` brown, `#a25340` rust, `#f4f0e9` cream, `#202022` ink. Exact original CSS values not exposed by browser tools; marked as estimates, not claimed sampled exact values.
- M Design observed type system: geometric sans for nav/body/hero and elegant high-contrast serif for section headings. This build uses DM Sans and Playfair Display substitutes; original font-family could not be established from available computed-style tooling.
- Container: outer content inset about 40 px on 1265 px screenshot; desktop cards use three equal columns and 30 px gutters. Approximate.

## Interactions observed
- M homepage hero exposes previous/next buttons and slide indicators; no interaction timings verified.
- Lifetime homepage has a multi-slide image carousel, visible controls in snapshot. This recreation displays a static image with decorative arrow controls (not wired to multiple slides) — unresolved interaction gap.
- Navigation links and calls to action are functional. Contact submission uses mailto handoff and clearly states no server submission. Reduced-motion CSS applied.

## Asset inventory
Official Lifetime Design-hosted photographs downloaded from WordPress media URLs; no M Design Group imagery or written content used. Filename-to-source mapping, roles and copyright caveat are recorded in `docs/asset-sources.md`. Image subject-to-project mapping not independently confirmed, so generic captions are used.
