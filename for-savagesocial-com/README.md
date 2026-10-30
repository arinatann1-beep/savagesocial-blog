# Drop-in files for the live savagesocial.com site

These are NOT for this repo. This repo is not what serves savagesocial.com.
The live site is a separate Netlify site built from a different GitHub repo.

## What is here

- `35-content-triggers.html` — the finished post, built in the live blog's design
  (cream #f5f1ea, ink #2a2522, orange #ff6b1a, Space Grotesk over Open Sans).
  It uses the same head, header, footer, Meta Pixel and GA tags as
  `/blog/how-to-film-reels-on-your-phone`, and it loads `../styles.css?v=13`.

- `blog-card-snippet.html` — the card for the `/blog/` index grid.

## Install into the live site repo

1. Put `35-content-triggers.html` wherever `how-to-film-reels-on-your-phone`
   lives, using the same naming pattern so the URL comes out as
   `/blog/35-content-triggers`.
2. Paste the card snippet at the top of `<div class="blog-grid">` on the blog index.
3. Deploy.

## Then

The ChatPlace automation «TRIGGERS» to Comment is Paused and its button points at
`savagesocial.com/blog/35-content-triggers-that-stop-the-scroll/`. Once the post is
live, that URL needs updating to the real slug and the automation can be switched on.
