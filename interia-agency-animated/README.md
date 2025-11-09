
# Interia Agency — Static Website (No Build Step)

A lightweight, multi-page static site using Tailwind via CDN.
Edit text directly in the HTML files using the GitHub web editor — no local setup required.

## Pages
- `index.html` (Home)
- `about.html` (About)
- `what-we-offer.html` (Services)
- `case-studies.html` (Portfolio)
- `contact.html` (Contact; wired to Formspree placeholder)

## Quick Deploy (Vercel)
1. Create a new GitHub repo and upload all files.
2. Go to vercel.com → New Project → Import your repo → Framework preset: "Other".
3. Deploy. Your site will be live at a Vercel URL (add a custom domain later).

## Edit Without Code
- Open any page (e.g., `index.html`) on GitHub, click the pencil icon, edit copy, Commit.
- Changes are auto-deployed on Vercel in under a minute.

## Contact Form
- The form posts to a Formspree endpoint included as an example.
- Replace the `action` URL in `contact.html` with your own Formspree endpoint after you create it.

## Customize
- Replace `assets/logo.svg` with your real logo.
- Swap `assets/placeholder.svg` for your work visuals.
- Update colors in the Tailwind `tailwind.config` object in the `<head>` of each file.
- Change buttons/CTAs as needed.

## Next Steps (Optional Upgrades)
- Convert to Next.js + a CMS (Decap or Notion) if you want an `/admin` editor later.
- Add analytics (Google Analytics) via a small `<script>` in `<head>`.
- Add SEO meta per page (title/description tags).
