# Pearl & Shetty — Creative Archive

A static website bringing together the books, stories, collaborations, posters, and creative projects associated with Soham Shetty and Tom Pearl.

## Project structure

```text
pearl_shetty_site/
├── index.html
├── README.md
└── assets/
    ├── fall-of-indus-poster.png
    ├── rangers-conservation-cover.png
    ├── two-films-poster.png
    └── whale-legacy-poster.png
```

## Run locally

No build step, package installation, or framework is required.

- Open `index.html` directly in a browser, or
- From this directory, run `python3 -m http.server 8000` and visit `http://localhost:8000`.

## Deploy to Vercel

This is a static HTML site.

1. Extract the ZIP file.
2. Put the contents of the `pearl_shetty_site` folder at the root of a GitHub repository. Make sure `index.html` is at the repository root (not nested one folder deeper).
3. Import that repository into Vercel.
4. Use the **Other** framework preset if Vercel asks for one.
5. Leave the build command and output directory empty/default; there is no build process.
6. Deploy. Future pushes to the connected production branch will trigger deployments.

Alternatively, use Vercel's dashboard to deploy the extracted folder as a static project.

## Updating the site

- Edit the text and page sections directly in `index.html`.
- Keep image filenames in `assets/` unchanged unless you also update their references in `index.html`.
- To add a poster, copy the image into `assets/` and add a corresponding gallery item in the HTML.
- The site currently has no database, CMS, login system, or server-side functionality.

## Content and accuracy notes

- The site is an initial archive/portfolio build. Confirm titles, publication details, project status, and biographies with Soham and Tom before treating every description as final.
- Tom's biography is intentionally limited to details established in the project context; add further personal or career details only after Tom confirms them.
- The whale-reproduction material should be described as a literature-review/draft project pending appropriate subject-matter review, not as peer-reviewed original research.
- Poster artwork is included as supplied project artwork. Check that the people depicted, titles, and credits are accurate before public promotion.

## Credits

Website developed by **Itikaas Ranjith**.

Content and project descriptions should be credited to their respective creators. Confirm image and text permissions before publishing or redistributing the site publicly.
