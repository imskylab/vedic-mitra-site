# Vedic Mitra — public pages (moved)

These pages now live in **[imskylab/imskylab.github.io](https://github.com/imskylab/imskylab.github.io)**:

- Landing page: https://imskylab.github.io/vedic-mitra/
- Privacy policy: https://imskylab.github.io/vedic-mitra/privacy/

**This repository is not retired, and its Pages site must stay published.** The old addresses still
have to resolve:

- `SupportLinks.PRIVACY_POLICY` is a `const val` compiled into v1.0.0 through v1.1.0, so every copy
  of the app already installed opens `/vedic-mitra-site/privacy/` and cannot be changed.
- The Google Play listing's privacy-policy URL must resolve for the listing to stay valid.
- The policy's own text promises that new versions are published "at the same address".

Both pages here are therefore redirects. GitHub Pages cannot serve a 301, so they are meta refreshes
carrying a `rel="canonical"` to the new address and `noindex`, with a visible link as a fallback.

`logo.png` is kept because the old social-card metadata pointed at it, and links shared earlier may
still fetch it.

The app itself is proprietary and its source is not public.
© 2026 Jayvardhan Potabatti. All rights reserved.
