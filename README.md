# Libaas Edit — Shop the Looks

A one-page affiliate shop: each post shows an outfit photo, with two
tag-style buttons underneath that send shoppers straight to your Myntra
affiliate links. Pure HTML + CSS — no build step, so it works as-is on
GitHub Pages.

## Host it on GitHub Pages

1. Create a new GitHub repo and push this whole folder to it.
2. In the repo: **Settings → Pages → Build and deployment → Deploy from
   branch → main → / (root) → Save**.
3. Your site goes live at `https://<your-username>.github.io/<repo-name>/`.

## Add a new outfit post

1. Add your new photo(s) to the `images/` folder.
2. Open `index.html` and find the comment that says:
   `NEW OUTFIT POST — copy everything from here...`
3. Select everything from `<article class="post">` down to the matching
   `</article>` and copy it.
4. Paste the copy right after the last post (still inside
   `<main class="feed">`).
5. In your pasted copy, update:
   - the two `src="images/..."` file names → your new photos
   - the two `href="..."` links → your new Myntra affiliate links
   - the item names and prices (`tag-item` / `tag-price`)
6. Save, commit, push — it's live.

You can repeat this for as many posts as you like; each one is fully
self-contained, so there's nothing else to edit.
