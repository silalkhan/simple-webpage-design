# 1st-project

Live demo: https://celebrated-sunflower-3e7725.netlify.app/

Quick start

- Install dependencies:

```bash
npm install
```

- Run dev server:

```bash
npm run start
```

- Build for production:

```bash
npm run build
```

Deploy to Netlify

- Connect your Git repo in Netlify and set:
  - Build command: `npm run build`
  - Publish directory: `dist`

Or run locally and drag the `dist/` folder into Netlify's deploy area after `npm run build`.

Notes

- `package.json` already contains `start` (`parcel index.html`) and `build` (`parcel build index.html`).
- Add a `_redirects` file to `dist/` with `/* /index.html 200` if using client-side routing.
