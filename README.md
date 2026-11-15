# Finance Calculators & Tools Hub

A collection of interactive financial calculators and web utilities hosted on GitHub Pages from a single repository.

## 🚀 Live Site Structure

This repository is structured to support multiple independent web applications:

| Site / Tool | Directory Path | Description |
| :--- | :--- | :--- |
| **Portal Hub** | `/` (`index.html`) | Landing page linking to all available tools |
| **FD & Auto-Renew Calculator** | `/FD calculator/` | Interactive Fixed Deposit and auto-renewal growth simulator |

### How to Add More Sites
To add another site or calculator to this repo:
1. Create a new directory (e.g. `sip-calculator` or `tax-estimator`).
2. Place your site's files inside with an entry point named `index.html`.
3. (Optional) Add a link/card to the new tool inside the root [`index.html`](index.html).

## ⚙️ Enabling GitHub Pages
1. Go to your repository on GitHub: **Settings** > **Pages**.
2. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
3. Choose the `main` branch and `/ (root)` folder, then click **Save**.
4. GitHub Pages will publish the site at:
   `https://<your-username>.github.io/finance/`
