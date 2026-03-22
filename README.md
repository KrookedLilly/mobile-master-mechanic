# Mobile Master Mechanic — Website

Static website for **Mobile Master Mechanic**, a 24/7 mobile auto repair service based in Spokane Valley, WA. Owner Shawn provides on-site auto repair at your home, office, or roadside.

## Tech Stack

- **HTML** — single `index.html` file
- **Tailwind CSS** — loaded via Play CDN (no build step)
- **Alpine.js 3.14.9** — loaded via CDN for mobile navigation toggle
- **Google Fonts** — Oswald (headings) + Roboto (body)

No build tools, no npm, no bundlers. The site works as-is with static file hosting.

## Deploying to GitHub Pages

1. Push this directory to a GitHub repository.
2. Go to **Settings > Pages** in the repository.
3. Under **Source**, select **Deploy from a branch**.
4. Choose the **main** branch and **/ (root)** folder.
5. Click **Save**. The site will be live at `https://<username>.github.io/<repo-name>/` within a few minutes.

To use a custom domain, add the domain to the `CNAME` file and configure DNS with your registrar.
