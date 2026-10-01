# React App - Render Ready

## Run locally

```bash
npm install
npm run dev
```

Open the local URL shown by Vite.

## Test production build

```bash
npm run build
npm run preview
```

## Deploy on Render

1. Upload this project to GitHub.
2. In Render, choose **New > Static Site**.
3. Connect the GitHub repository.
4. Use:

Build Command:
```bash
npm install && npm run build
```

Publish Directory:
```text
dist
```

5. Create the site.

The included `render.yaml` contains the same basic deployment configuration.

## Important

Replace the example content in `src/App.jsx` and the CSS files with your actual website/app code.
