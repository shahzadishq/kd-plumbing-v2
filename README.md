# KD Plumbing — Cinematic V2

A NEW design direction: cinematic dark-green/copper hero, large elegant typography, interactive 3D plumbing assembly, editorial photography, GSAP scroll reveals, Lenis scrolling, responsive services and contact sections.

## Run

```bash
npm install
npm run dev
```

## Build and deploy

```bash
npm run build
```

Upload **dist/** to Netlify (not the source ZIP). Or connect the GitHub repository to Netlify: build command `npm run build`, publish directory `dist`.

For GitHub Pages repository `kd-plumbing`, run `GITHUB_PAGES=true npm run build` and deploy `dist`.

## Before publishing for client

- This is a **design concept**, not confirmed client copy. The previous KD Plumbing site was not reliably accessible to verify business facts.
- Replace placeholder service descriptions, stock imagery and contact details with verified KD Plumbing content.
- The contact CTA is intentionally disabled until a real email/phone is provided. Update it in `src/main.jsx`.
- Review stock-image licenses and replace with client-owned photography where possible.
- Test in real browsers and devices; 3D requires WebGL and can be resource-intensive.
- Reduced-motion users skip GSAP/Lenis motion; test accessibility and performance before production.
- This design was not yet validated against the original image mockup in a browser screenshot. It is a close visual reinterpretation, not a pixel-perfect reproduction.
