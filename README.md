# Tindahan Sim — Store Owner Simulator

A playable browser-based convenience-store management game for desktop and Android browsers. Built with plain HTML, CSS and JavaScript. No Node.js, build step, or paid dependencies.

## Play locally
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge, Firefox, or another modern browser.
3. The game runs locally; the optional Google Font needs internet, but the game itself does not.

## How to play
- Customers appear in the queue. Click **Checkout customer** or press Enter on desktop to complete the first customer's order.
- Tap/click a shelf in the store scene or choose **Manage** under Inventory to buy stock at wholesale cost.
- Upgrade your shop with Extra shelves, Store makeover, Cold drinks fridge, and Hire cashier.
- The cashier automatically serves available orders and costs ₱180 per day.
- **Close Day & Collect** shows your daily report and applies wages and the customer-happiness bonus.
- Progress autosaves in the browser using localStorage. Save data is local to that browser/device and does not sync between devices.

## Publish using GitHub Pages
1. Sign in at https://github.com.
2. Click the **+** button in the top-right, then **New repository**.
3. Name it `store-owner-simulator`. Choose **Public** (recommended for a free GitHub Pages setup), then click **Create repository**.
4. In the new repository, click **Add file → Upload files**.
5. Upload `index.html`, `style.css`, `game.js`, and `README.md` directly into the repository's root (not inside another folder).
6. Scroll down and click **Commit changes**.
7. Open the repository's **Settings** tab.
8. In the left sidebar, open **Pages** under **Code and automation**.
9. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
10. Select branch **main** and folder **/(root)**, then click **Save**.
11. Wait a minute or two and refresh Settings → Pages. GitHub will show the published URL, usually `https://YOUR-USERNAME.github.io/store-owner-simulator/`.
12. Open that URL on your PC and Android phone. On Android Chrome, use the menu → **Add to Home screen** to create a shortcut.

## Update later
Commit new versions of the files to the same repository. GitHub Pages automatically republishes after a commit.

## Controls
- Desktop: mouse clicks; Enter checks out the first customer; Escape closes a dialog.
- Android: tap buttons and shelves; the layout adapts to narrow screens.
- The scene is a lightweight 2.5D/isometric-style canvas illustration, not a full polygonal 3D engine.
- Saves are per browser/device; GitHub Pages does not sync your progress between devices.

## Files
- `index.html` — interface and page structure
- `style.css` — responsive styling
- `game.js` — game mechanics, scene rendering, inventory, customers, upgrades, and saving
