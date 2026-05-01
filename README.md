# nazaretests

Public prototypes and experiments for GitHub Pages.

## Structure

- `index.html`
  - Landing page for the site
- `format-spark/index.html`
  - Random format idea generator
- `intervention-spark/index.html`
  - COM-B intervention idea generator for Stage 3 barriers
- `reuters-innovation-spark/index.html`
  - Reuters innovation card randomiser using the extracted “What if…” prompts

## Publish with GitHub Pages

1. Push these files to the `nazaretests` repository.
2. In GitHub, open `Settings` -> `Pages`.
3. Under `Build and deployment`, choose `Deploy from a branch`.
4. Publish from:
   - Branch: `main`
   - Folder: `/root`

The site URLs should then be:

- Landing page:
  - `https://wilnazare.github.io/nazaretests/`
- Format spark:
  - `https://wilnazare.github.io/nazaretests/format-spark/`
- Intervention spark:
  - `https://wilnazare.github.io/nazaretests/intervention-spark/`
- Innovation spark:
  - `https://wilnazare.github.io/nazaretests/reuters-innovation-spark/`

## Adding more experiments later

1. Create a new folder in the repo.
2. Put an `index.html` file inside it.
3. Add a link card for it in the root `index.html`.
