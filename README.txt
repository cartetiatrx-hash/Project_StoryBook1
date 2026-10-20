INKVERSE — ANIME MANGA STORYBOOK

HOW TO OPEN IN VS CODE
1. Download and extract the ZIP.
2. Open VS Code.
3. Select File > Open Folder.
4. Choose the extracted Anime_Manga_Storybook folder.
5. Open index.html. For best testing, install Live Server and click Go Live.

FILES
- index.html: homepage with all 30 manga cards
- style.css: all styling and responsive layout
- script.js: search, genre filter, dark/light theme, details popup, like button, reading progress, back-to-top
- stories/story-1.html through story-30.html: one chapter per story
- images/: local artwork plus SVG covers and chapter illustrations used as image fallbacks

PUBLISH ON GITHUB PAGES
1. Create a GitHub repository.
2. Upload the CONTENTS of the Anime_Manga_Storybook folder to the repository root. Keep index.html, style.css, script.js, stories/, and images/ together; do not upload only index.html.
3. In the repository, open Settings > Pages and choose Deploy from a branch. Select the main branch and /(root), then save.
4. Wait for GitHub Pages to finish deploying, then open the published URL. All page and image links are relative, so the site also works when the repository URL includes a project name.

Each story page uses its own matching image when that file is available. If an image cannot load, the matching local SVG cover remains in place. Wind Breaker uses `images/wind.webp`.

All chapter stories are original short fiction, not copied manga chapters. The numbered animemes image files are supplied artwork; make sure you have permission to publish them publicly. If an image is missing or unsupported, the project uses its original decorative SVG artwork instead.
