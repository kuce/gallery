# Gallery

A Hugo photo gallery using [hugo-theme-gallery](https://github.com/nicokaiser/hugo-theme-gallery).

## Add an album

Create a folder under `content/` with an `index.md` page bundle, then add the album's JPEG files beside it:

```text
content/
└── summer-2026/
    ├── index.md
    ├── photo-001.JPG
    └── photo-002.JPG
```

The album appears automatically on the homepage. Use the existing `content/halloween/index.md` as the metadata template. Keep original photos in JPEG format; the theme does not support WebP reliably.

## Local build

Run Hugo from the repository root:

```powershell
hugo.exe server
```

GitHub Actions deploys the site to GitHub Pages whenever `main` is updated.