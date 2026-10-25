# Image2PDF

Browser-only tool: pick a folder of images, tick/sort them, export one PDF or PPTX (max 750 images). No uploads, no dependencies.

## Publish on GitHub Pages
1. Create a repository and upload `index.html` (and this README) to the root.
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`.
3. Open `https://<your-username>.github.io/<repo>/`.

## Notes
- Sort by name, date modified, date taken (JPEG EXIF), size, type, or drag rows for manual order. Browsers do not expose a file's true creation date, so "date modified" is used.
- Folder picking needs a desktop browser (Chrome, Edge, Firefox, Safari). On phones use "Select individual images".
- HEIC/TIFF/RAW are not readable by browsers and are skipped.
