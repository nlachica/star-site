# Hermes Star Personal — public information site

Static homepage and privacy policy. This repository contains no assistant backend or connected account data.

## Files

- `index.html`: about Star, its connections, and its independent ownership.
- `privacy/index.html`: privacy policy, data flows, permissions, retention, revocation, hosting, and support contact.
- `styles.css`: shared responsive styling using locally available fonts.
- `.nojekyll`: disables Jekyll processing when deployed to GitHub Pages.
- `CNAME`: intended custom domain, `star.arivity.com`.
- `README.md`: public documentation for this site.

The policy date is November 15, 2026. Descriptions reflect the operator-supplied architecture; this site does not certify implementation or claim Google approval, verification, or OAuth production status.

## Preview

Open `index.html` locally, or serve this directory with a static HTTP server, for example:

```sh
python3 -m http.server 8765 --bind 127.0.0.1 --directory .
```

Then visit `http://127.0.0.1:8765/` and `http://127.0.0.1:8765/privacy/`.

## Public-content boundary

Only public static site files belong here. Do not add credentials, private configuration, personal documents, or assistant data.

There are no scripts, analytics, forms, application login, added cookies, or external asset dependencies.

GitHub Pages is the intended public host and may process request metadata for delivery and security under its own privacy statement. Creating these files and the `CNAME` does not publish a site, configure DNS, enable HTTPS, or change Google OAuth settings. Publication and any DNS configuration are separate actions.
