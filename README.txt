ROOM12 – Partner Story: self-hosting package
=============================================

Contents
  index.html      the page (everything is self-contained; no external services)
  img/            images, logos, share image, and the teaser film (teaser-v3.mp4)
  fonts/          Oswald and Public Sans, served locally (no Google Fonts calls)
  favicon.svg     browser tab icon

To publish
  Upload the whole contents of this folder (keep the folder structure) to the
  web root or a sub-folder, e.g. https://yourdomain/room12/
  - Netlify Drop: drag this folder onto https://app.netlify.com/drop
  - University web space / any static host: upload as-is
  index.html must stay next to the img/ and fonts/ folders.

One edit after you know the final address (for nice link previews)
  In index.html, change
      <meta property="og:image" content="img/share.jpg">
  to the full address, e.g.
      <meta property="og:image" content="https://yourdomain/room12/img/share.jpg">
  LinkedIn, WhatsApp, Teams and Slack need the full URL to show the preview image.

Notes
  - The film is ~15 MB and streams from the page; most hosts handle this fine.
  - Contact: Prof. Richard Koeck, r.koeck@liverpool.ac.uk
