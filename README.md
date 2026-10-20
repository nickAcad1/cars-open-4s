# Nick 4 Speed · car models

Game-ready car bodies for [Nick 4 Speed](https://speed.nick-academy.com), loaded by the game through the jsDelivr CDN.

- `cars/<id>.glb`: body without wheels, nose along −Z, wheels standing on y = 0. Textures are WebP, geometry is meshopt-compressed.
- `cars/<id>-rim.webp`: the rim, face-on, with transparency.
- `cars/cars.json`: names, specs (mass, power, drag, lift, centre of gravity, grip) and the measured wheel positions.

These files are generated. Edit the sources in the game repository and rebuild with `tools/build-cars.mjs`.
