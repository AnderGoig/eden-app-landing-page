# Eden landing page (moved)

Eden's website is now **https://eden.latelunch.app/**.

This repo used to build Eden's landing page on GitHub Pages at `https://andergoig.github.io/eden-app-landing-page/`. It now only holds redirect pages, so old links keep working, including the privacy link in older versions of the app.

| Old URL | Goes to |
| --- | --- |
| `/` | https://eden.latelunch.app/ |
| `/privacy/` and `/privacy` | https://eden.latelunch.app/privacy |
| `/changelog/` and `/changelog` | https://eden.latelunch.app/ |
| Any other path (`404.html`) | https://eden.latelunch.app/privacy if the path mentions "privacy", otherwise https://eden.latelunch.app/ |

GitHub Pages can't send server redirects, so each page uses an instant meta refresh, a JavaScript redirect and `rel=canonical`. `.nojekyll` makes Pages serve the files as they are.

Don't delete this repo or turn off its Pages site: Eden 1.9.2 and earlier open the old privacy URL from inside the app.

The original site was built from [emilbaehr/automatic-app-landing-page](https://github.com/emilbaehr/automatic-app-landing-page) (MIT, see `LICENSE`).
