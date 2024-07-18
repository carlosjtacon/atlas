## atlas.carlosjtacon.com

My personal atlas website, to keep track of what I do - when, where, with who...
I tend to forget all the details, so I want a way to remember.

### Different pages:
- [ ] `about` - What is Atlas.

- [ ] `globe` - 3D globe view, rendered with three.js with 1. pins that show different trips coordinates and 2. connection lines that follow the personal timeline steps.

- [ ] `mappa` - 2D vector world map minimal color theme with all the tracks displayed and framed in a bounding square.

- [ ] `whoami` - Show carlos/person data, draw timeline and maybe also add trips on it (two different levels in the timeline).

- [ ] `stream` - Timeline view for all posts with a tag showing the category. Can be also the RSS. Maybe it could be filtered by metadata (people, transportation...)

- [ ] `category/index` - Timeline view page for categories (days, timeline, tracks, trips). Maybe it could be filtered by metadata (people, transportation...)

- [ ] `category/post` - Article view page for longer format text for every category (days, timeline, tracks, trips) use a different layout per category to adapt the metadata.

### Types of data / posts:
- [person.yml](_people/readme.md) ???????? - Maybe in `_data`
- [day.yml](_posts/days/readme.md)
- [timeline.yml](_posts/timeline/readme.md)
- [track.yml](_posts/tracks/readme.md) ???????? - Maybe in `_data`
- [trip.yml](_posts/trips/readme.md)

### Design language
- [ ] First letter of each post as a lombardic medieval capital letter with colors maybe
- [ ] Medieval-inspired carved wooden engraving style for website elements
- [ ] Logo design can be the wood mold stamp in 3d / stamped in 2d
- [ ] Atlas titan character illustrated for about page
- [ ] Animation of hover elements and show an animation of the carving process


Capital letters:
- We can maybe use a regular font with a custom style but put a bg image, maybe there is a border property to separate it. We could animate a svg for the build up of the letter.
- We can have a way to override the generic capital letters with a custom drawn one for the trip.

Engraving style css:
- Find a way to add texture to text

----------------------------------

#### Resources to (maybe) use

- https://globe.gl
- https://openlayers.org
- https://tilemaker.org
- https://protomaps.com
- http://download.geofabrik.de
- https://maplibre.org/maplibre-gl-js
- https://leafletjs.com
- http://mpetazzoni.github.io/leaflet-gpx/
- https://github.com/mapbox/togeojson
