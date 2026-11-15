# BijliBill.pk
Pakistan electricity bill calculator (static site, no build step).

## Deploy on Vercel
1. Push this repo to GitHub.
2. vercel.com > Add New > Project > import the repo > Deploy (Framework: Other, no build command).
3. Replace `utilitybill.vercel.app` in index.html, robots.txt, sitemap.xml with your real URL.

## Update tariff
Edit the `RATES` block at the top of the script in index.html, then `git commit` and `git push`. Vercel redeploys automatically.
