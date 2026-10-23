YOUR HUB (independent of Claude)

Open index.html in any browser. That is the hub. web.html is the connections map.
Every app opens from the hub. Keep all these files in one folder.

For all pages to share one browser address (needed later for shared data), serve the folder:
  python3 -m http.server 8000      then open http://localhost:8000
Or upload the whole folder to a static host (Netlify Drop, GitHub Pages, Cloudflare Pages) to open it from any device.

Data is saved in the browser you use, per address. Clearing browser data deletes it.
Fonts load from Google Fonts, so the first load needs internet.
