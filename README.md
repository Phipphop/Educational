# Educational
Simple webpages for visualizing and experimenting with concepts

## Solar Grid (interactive game)
`solar-grid.html` is a self-contained browser game about renewable energy, storage,
and efficiency. Power a mining outpost through lengthening day/night cycles: place
solar panels (daytime only), bank surplus in batteries, distribute power through a
pylon network (each hop loses a little energy), and run extractors that only work
while powered. The richest ore — Iridium — can only be mined at night off stored
battery power. Deliver 30 Iridium to win; lose if your Hub goes dark for 60s.

No build step or dependencies — just open the file in a browser. (Add `?debug=1` to
the URL to expose a small testing API on `window.__sg`.)
