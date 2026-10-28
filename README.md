# Mulaqat – Dating Website

A single-page dating website with a logo splash screen, a swipe-card demo, features section and a signup form.

## Files

- `index.html` – the whole website (HTML, CSS, JavaScript and logo in one file)
- `README.md` – this file
- `.gitignore` – files Git should skip
- `LICENSE` – MIT license

## Run it

Open `index.html` in any browser. No install or build step needed.

## Put it online with GitHub Pages (free)

1. Create a new repository on GitHub and upload these files.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then click **Save**.
4. After a minute, your site is live at `https://<your-username>.github.io/<repo-name>/`.

## Note about the signup form

The signup form only saves data when the page runs inside Claude. On GitHub Pages it works as a demo: it checks the fields and shows the success message, but it does not store anything. To collect real signups, connect a backend such as Supabase, Firebase or Formspree.

## Customize

- Name, text and colors: edit `index.html` (colors are the `--coral`, `--gold`, `--bg` variables near the top).
- Sample profiles: edit the `P` list in the `<script>` section.
