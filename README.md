# VYPJ — Vietnam Youth Policy Journal

This is a ready-to-deploy static rebuild of VYPJ using the supplied article archive.

## What is included
- Homepage and publication archive
- Search
- Individual article pages
- About page
- 19 non-outline documents converted into editable Markdown article records
- `.pages.yml` configuration for Pages CMS, so articles can be edited through a web interface after the repository is connected

## Fastest way to put it online
1. Create a GitHub repository named `vypj`.
2. Upload the contents of this folder to the repository (not the folder itself).
3. Turn on GitHub Pages for the repository, using the `main` branch and `/ (root)`.
4. Go to Pages CMS and sign in with GitHub, then select the `vypj` repository. The Publications collection will let you edit the Markdown article records without writing code.

The generated site itself is plain HTML/CSS/JS, so GitHub Pages can host it for free. Changes made through the CMS commit back to the repository and become live on the site after GitHub Pages rebuilds.

## Editorial note
One obvious outline document was excluded. The archive also contains two pieces on corporal punishment that appear related/revised; both are retained so you can decide which version belongs in the public archive.
