# Flux Privacy Policy

A responsive privacy page for the [Flux](https://github.com/Gaurav598/Flux) demo/test ride-booking apps. The site is a single static `index.html` and needs no build process.

## Source review

The policy was written against Flux’s public source on 9 October 2026. It reflects phone authentication, user and rider records, ride/location fields, notifications, upload code, and the current free-subscription payment service. It does not claim that every optional integration is active in every demo build. The owner confirmed there is no formal or automated deletion process, no established standard procedure for manual deletion across the backend, Firebase, and S3, and no fixed retention period. The policy discloses these gaps and the planned workflow without promising a deletion timeline.

The support address was supplied by the repository owner. Do not send privacy requests through public GitHub issues.

## Local preview

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/`.

## Publishing

This repository is laid out for GitHub Pages from `main` and `/ (root)`. The expected address after Pages is enabled is `https://gaurav598.github.io/PrivacyPolicy/`. Verify the published page before sharing that URL. See [GitHub’s branch publishing instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
