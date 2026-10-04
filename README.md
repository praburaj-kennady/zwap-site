# Zwap — support, privacy and accessibility pages

The public pages for **Zwap**, a currency converter, unit converter and world clock for
iPhone, served by GitHub Pages at **https://zwap.praburajkennady.me**:

- [`/`](https://zwap.praburajkennady.me/) — about Zwap
- [`/support/`](https://zwap.praburajkennady.me/support/) — contact and common questions (the App Store support URL)
- [`/privacy/`](https://zwap.praburajkennady.me/privacy/) — the privacy policy (the App Store privacy policy URL)
- [`/accessibility/`](https://zwap.praburajkennady.me/accessibility/) — how Zwap works with VoiceOver, Voice Control, larger text and the other accessibility features (the App Store accessibility URL)

The domain is a Cloudflare CNAME, `zwap` → `praburaj-kennady.github.io`, with the proxy
off ("DNS only") so GitHub can issue its HTTPS certificate. `CNAME` in this repo names it;
the old `praburaj-kennady.github.io/zwap-site/` address redirects here.

Plain HTML, one stylesheet, and a small inline script that names each page transition
and, in Arc, changes the page in place; no trackers, no third-party requests. The
app's own source lives in a separate, private repository.

Typeface: [Nunito](https://github.com/googlefonts/nunito) by Vernon Adams, Cyreal and
Jacques Le Bailly, under the SIL Open Font License 1.1 — see `assets/fonts/OFL.txt`.

© 2026 Praburaj Kennady. All rights reserved.
