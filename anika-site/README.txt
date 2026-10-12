HOW TO PUT THIS SITE ON GITHUB PAGES (so your photo shows in the browser tab)

1. Go to github.com and click New repository.
2. Name it exactly:  anikasola.github.io   (your username + .github.io)
   Set it to Public. Click Create repository.
3. Click "uploading an existing file" and drag in EVERYTHING from this folder:
   index.html, favicon.png, favicon-32.png, apple-touch-icon.png,
   icon-192.png, icon-512.png, og-image.png
   Then click Commit changes.
4. Go to Settings > Pages. Under "Build and deployment" choose
   Source: Deploy from a branch, Branch: main, Folder: / (root). Click Save.
5. Wait about a minute. Your site will be at  https://anikasola.github.io/
   Your photo will show in the browser tab, and og-image.png is the picture
   that appears when you share the link.

If you name the repository something else (like "portfolio"), the address becomes
https://anikasola.github.io/portfolio/ and you should change the og:image line near the
top of index.html to match that address.
