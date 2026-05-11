# Rare Founders × Silverstone — Private BTCC Weekend

Static landing page for the Rare Founders × Silverstone BTCC private invitational
(26–27 September 2026). Single HTML file plus an `images/` folder.

## Hosting on GitHub Pages

1. This repo is already structured for GitHub Pages.
2. Go to **Settings → Pages**.
3. Under "Source", choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save. The page goes live within ~1 minute at:
   `https://<your-username>.github.io/silverstone-invitational/`

## Custom domain (optional)

To serve at e.g. `silverstone.rarefounders.com`:

1. In **Settings → Pages → Custom domain**, enter the subdomain.
2. In your DNS provider, add a CNAME record:
   - Host: `silverstone`
   - Target: `<your-username>.github.io`
3. Wait for DNS propagation (~10 min). GitHub auto-issues SSL.

## Updating

Drag a new `index.html` (or any image) into the repo via the GitHub web UI →
**Add file → Upload files** → Commit. Live ~30 seconds later.

## Form

The "Register Your Interest" buttons all open the ClickUp waitlist form in a new tab:
https://forms.clickup.com/90151333967/p/f/2kyq0c2f-7355/Y5W15NQOEP05SBCLS2/form
