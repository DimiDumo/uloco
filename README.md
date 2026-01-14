# Uloco - Artist Homepage Versions

A collection of different landing page/homepage designs for an artist website. Each folder represents a different version that can be previewed directly via GitHub Pages.

## Structure

```
uloco/
├── v1/          # Version 1 - [description]
│   └── index.html
├── v2/          # Version 2 - [description]
│   └── index.html
└── ...
```

## Live Previews

Each version is accessible via GitHub Pages:

- **Version 1**: https://dimidumo.github.io/uloco/v1/
- **Version 2**: https://dimidumo.github.io/uloco/v2/
- *(add more as you create them)*

## Usage

1. Create a new folder for each version (e.g., `v3/`)
2. Add an `index.html` file inside
3. Push to main branch
4. Access via `https://dimidumo.github.io/uloco/<folder-name>/`

## Development

To test locally, you can use any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve
```

Then navigate to `http://localhost:8000/v1/` etc.
