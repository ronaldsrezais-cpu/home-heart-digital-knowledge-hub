# Home & Heart Digital Knowledge Hub — Fresh Static Version

This is a clean Vercel-ready static website. It does not use Next.js, npm, package.json or package-lock.json, so there should be no dependency/build errors.

## Deploy on Vercel

- Framework Preset: Other
- Build Command: leave empty
- Output Directory: leave empty
- Install Command: leave empty

The website entry point is `index.html`.

## How to add resources

1. Upload your PDF/DOCX files into the `resources/` folder.
2. Open `index.html`.
3. Find the `const resources = [` list.
4. Add or edit an item and set `file: 'resources/your-file-name.pdf'`.

Example:

```js
{ icon:'📘', title:'New Guide', desc:'Description here.', audience:['Families'], topic:'Activities', file:'resources/new-guide.pdf' }
```

## How to add livestream link

Open `index.html`, find `Livestream`, and replace `Link not available yet` with your livestream URL or a button.
