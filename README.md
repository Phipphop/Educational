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

## Fuel Chain (interactive sim)
`fuel-chain.html` is a self-contained teaching sim for **Chapter 3 (The Invisible
Cost of Fuel)**. You build the entire gasoline supply chain yourself — pumpjack →
pipeline → refinery → export port → tanker across the sea → import port → trucks →
gas station — and a live Energy Ledger tallies the electricity and fuel the chain
quietly consumes just to put gas in a car. Reach the delivery goal and the payoff
screen shows how far that overhead electricity could have driven an EV directly,
with no rig, refinery, tanker, or truck. (This is Phase 1; Phase 2 will plug the
same cars into solar + batteries.)

No build step or dependencies — just open the file in a browser. (Add `?debug` to
the URL to expose a testing API on `window.__fc`: `tick`, `build`, `pipe`, `state`.)
