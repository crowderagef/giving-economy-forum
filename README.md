# Giving Economy Forum website

The website of the Giving Economy Forum (GEF), powered by Crowdera.

This is a static site with no build step. `index.html` holds every page (Home, About Us, The Community, Stories of Change, Contact). Pages switch by URL hash, for example `#about`. All photos and the logo live in `images/`.

## Publish with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, then pick `main` and `/ (root)`.
3. Save. The site goes live at `https://<account>.github.io/<repository>/` within a minute or two.
4. To use a custom domain such as `givingeconomy.org`, enter it under **Custom domain** and point the domain's DNS at GitHub Pages.

## Photo credits

- Singapore skyline at dusk (home page hero): Benh LIEU SONG, via Wikimedia Commons, licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
- All other photos: Giving Economy Forum and Crowdera event photography.

## Search and sharing

- Each main page has its own address (`/about/`, `/community/`, `/stories/`, `/contact/`), title, description and canonical link.
- Open Graph and Twitter tags use `images/share-2026.jpg` (1200x630) for link previews.
- The home page carries schema.org data for the organisation and the 9th Giving Economy Forum (25 Nov 2026, ONE°15 Marina, Sentosa).
- `sitemap.xml` and `robots.txt` point search engines at https://www.givingeconomy.org.
- `CNAME` sets the custom domain to www.givingeconomy.org.
- After DNS is live, add the site in Google Search Console and submit `https://www.givingeconomy.org/sitemap.xml`.
