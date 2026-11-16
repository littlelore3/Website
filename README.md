# Little Lore website (single-file version)

Everything — text, styles and all images — is inside `index.html`. There are no folders to upload, so nothing can go missing.

## Put it online with GitHub Pages

1. In your GitHub repository, delete the old `index.html`, `style.css` and `images` folder (or start a new repository).
2. Choose **Add file → Upload files**, drag in this `index.html` (and `.nojekyll` if you can see it), then click **Commit changes**.
3. In **Settings → Pages**, the source should be **Deploy from a branch**, branch **main**, folder **/ (root)**.
4. Wait a minute, then refresh your site with Ctrl+F5 (Cmd+Shift+R on a Mac).

## Before launch

Open `index.html` in a text editor and search for:
- `href="#"` on the "Buy on Amazon" button — replace `#` with your Amazon link.
- `[YOUR PRICE]` — replace with your price.
- The "NEWSLETTER" section — replace the input and button with your email provider's form code to collect sign-ups.
