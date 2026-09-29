LEONID DUKHOVNY — BARDS.RU STATIC ARCHIVE

OPEN ON YOUR COMPUTER
1. Extract this ZIP completely.
2. Double-click index.html.
Keep the songs and assets folders beside index.html.

PUBLISH ON GITHUB PAGES
1. Create or open your GitHub repository (use a public repository for free Pages).
2. Upload the EXTRACTED contents of this ZIP to the repository's main branch.
   index.html must be at the repository root, not inside an extra parent folder.
   Do not upload the ZIP itself: GitHub Pages does not unpack ZIP files.
   Preserve the songs/ and assets/ folder structure. Include .nojekyll if visible.
   If GitHub's browser uploader limits the batch size, upload the root files and
   assets first, then upload the song files to songs/ in two batches.
   Alternatively, copy all extracted files into a GitHub Desktop checkout and
   commit/push them together.
3. Open the repository's Settings > Pages.
4. Under Build and deployment, choose Source: Deploy from a branch.
5. Select main and /(root), then Save.
6. Wait for GitHub's deployment to finish. The Pages settings will show the URL.
   The website works at either a domain root or a repository subpath.

No PHP, Node.js, npm install, database, compilation, or application server is needed.
This package is ready to publish; GitHub Pages itself still needs to be enabled.
Official instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

CONTENTS
- index.html: author page from the requested November 12, 2024 archive.
- by-year.html: the original sort-by-year view, retrieved from the live website.
- songs/: all 108 distinct song pages linked from the author page.
- assets/: 16 original image/style assets, including the portrait and background.
- RECORDINGS.csv: all 23 recording links found across the song pages.
- SOURCES.json: sources and retrieval URLs for pages and assets.
- .nojekyll: indicates that this is a static site.

AUDIO LIMITATION
No audio files are included. All 23 recording links lead to YouTube/YouTube Music
(10 distinct recordings, including timestamped links to a concert).
The source pages contain no direct MP3 downloads. Attempts to retrieve all ten
recordings returned "Site Unavailable" instead of valid audio data. Invalid
responses have been removed rather than packaged as broken audio files.
The original listening/viewing links are retained, labeled "(онлайн)", and
require an internet connection. Their continued availability is controlled by
the external service.

PRESERVATION NOTES
The original Cyrillic text, lyrics, legacy layout and CSS are preserved.
93 song pages were retrieved from Wayback Machine; 15 used the live website
when an archived copy was unavailable. Individual source URLs are recorded in
SOURCES.json. The portrait and some assets also used live-site fallbacks.
Wayback toolbar, advertising scripts and third-party tracking images are absent.
Malformed music links beginning http://https:// were corrected.
Navigation outside this author and the 108 songs remains external and needs
internet access. Other authors, the full photo archive, guestbooks and the
site-wide search service are outside this two-level copy.

VERIFICATION
All 108 song pages have their original lyric text. All local HTML links, image
references and CSS asset references have been checked for existing targets.
No build step or server-side files are required. Browser screenshot verification
was unavailable in the execution environment.
