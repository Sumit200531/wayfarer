# wayfarer

A pocket galaxy you can fly around in the browser.

- ~95,000 stars, generated from a seed, in a spiral with dust lanes, nebulae and a glowing core
- star colours come from their actual surface temperature (blackbody approximation)
- ~750 brighter stars have names. Click one and the camera flies there
- every named star has its own planets: scorched rocks, ocean worlds, cold deserts, gas and ice giants, some with rings
- habitable zone and frost line are worked out from the star's brightness, so which planets end up where isn't random
- planets follow the naming convention astronomers use (Star b, Star c, ...) and year lengths come from Kepler's third law
- draw your own constellations by joining stars. Then turn the galaxy and watch them fall apart, because a constellation only looks like a shape from one spot
- logbook of every star you've visited
- "chart a new galaxy" gives you a completely different one

No build step and no framework. One HTML file plus three.js from a CDN.

## Run it

Open `index.html` in a browser. Or put it on GitHub Pages.

## Controls

Drag to rotate. Scroll or pinch to zoom. Click a bright star to travel to it. Esc goes back.
