CANADIAN HAT MAKER — STATIC REBUILD

Files:
- index.html
- felt.html
- straw.html
- custom-headwear.html
- restoration.html
- about.html
- contact.html
- styles.css
- script.js

DEPLOYMENT
Upload the whole folder to GitHub and connect the repo to Cloudflare Pages.
Build command: leave blank
Output directory: /
Framework preset: None

IMPORTANT
This version deliberately references existing CanadianHatMaker.com Shopify CDN images so it can preserve the original site's photography without bundling copied image files.
Before cancelling Shopify, download the original image assets and replace the remote URLs in the HTML/CSS with local /assets/... files. Otherwise Shopify-hosted images may stop working after the store is closed.

The contact form currently opens the visitor's email client. Wire it to your desired static form endpoint before production launch if required.
