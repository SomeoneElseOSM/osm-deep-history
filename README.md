# OSM Deep History

This is 99.9% based on https://github.com/osmlab/osm-deep-history with a few minor tweaks.

Changes:
* Map is currently not displayed (to allow more object versions to fit on the screen)
* The bottom scroll bar is moved up a bit more to work better on smaller screens.
* The default changeset link is to openstreetmap.org/changeset.
* An additional changeset link to https://overpass-api.de/achavi/ is also available.
* The default user link is to openstreetmap.org/user.
* An additional user link to https://hdyc.neis-one.org/ is also available.
* Uid is also displayed, and comments on the user's changesets, and their comments, are also shown.

Example deployment:
* [Node](https://map.atownsend.org.uk/osm-deep-history/#/node/4857559003)
* [Way](https://map.atownsend.org.uk/osm-deep-history/#/way/333067739)

To rebuild and test locally:

```
npm install
npm run build
npm start
```

Once rebuilt, just deploy behind a regular website - "bundle.js" contains all the code; no need to run "npm".
