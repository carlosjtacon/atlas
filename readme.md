## atlas.carlosjtacon.com

My personal atlas website, to keep track of what I do - when, where, with who...
I tend to forget all the details, so I want a way to remember.

### Different pages:
- [ ] `index` - List the different pages of the website.
- [ ] `stream` - Timeline view for all posts with a tag showing the category. Can be also the RSS. Maybe it could be filtered by metadata (people, transportation...)
- [ ] `globe` - 3D globe view, rendered with three.js with 1. pins that show different trips coordinates and 2. connection lines that follow the personal timeline steps.
- [ ] `mappa` - 2D vector world map minimal color theme with all the tracks displayed and framed in a bounding square.
- [ ] `line` - Timeline view of all posts, with different levels of view for timeline, days and trip items.
- [ ] `tracks` - List of gpx from static files.
- [ ] `persona` - Why Atlas and who am I. Show carlos/person data, draw timeline and maybe also add trips on it (two different levels in the timeline).
- [ ] `category/index` - Timeline view page for categories (days, timeline, tracks, trips). Maybe it could be filtered by metadata (people, transportation...)
- [ ] `category/post` - Article view page for longer format text for every category (days, timeline, tracks, trips) use a different layout per category to adapt the metadata.

### Types of data / posts:
- [day.yml](_posts/days/readme.md)
- [trip.yml](_posts/trips/readme.md)
- [timeline.yml](_posts/timeline/readme.md)

- [tracks](assets/tracks/readme.md)
- [json data](assets/json/readme.md)

### Design language
- [ ] First letter of each post as a lombardic medieval capital letter.
    - We should have a generic alphabet of letters but can have a way to override the generic capital letters with a custom drawn one for the trip.
    - We can use a background / foreground image animated colored SVG or Lottie for carving animation, while keeping the font with a background color border. 
        1. Static background image photo / raster. Choose design from the post front matter.
        2. Vectorize image, wood carving style.
        3. Add foreground image.
        4. Animate it.
    - We can also create a custom font with dynamic width instead.
- [ ] Medieval-inspired carved wooden engraving style for website elements like navigation, menus... etc
    - Animation of hover elements and show an animation of the carving process
- [x] Find a way to add texture to text, to show printing inperfections as if printed.
- [ ] Ability to have custom css for a post or page - I can define diffenent themes css and then drive them with a post variable to override accent color... etc
- [ ] Atlas logo design can be the wood mold stamp in 3d / stamped in 2d
- [ ] Atlas titan character illustrated for about / whoami page by Alix

----------------------------------

#### Resources to (maybe) use

**Maps:**
- https://globe.gl
- https://openlayers.org
- https://tilemaker.org
- https://protomaps.com
- http://download.geofabrik.de
- https://maplibre.org/maplibre-gl-js
- https://leafletjs.com
- http://mpetazzoni.github.io/leaflet-gpx/
- https://github.com/mapbox/togeojson

**ActivityPub:**
- https://0xacab.org/sutty/jekyll/jekyll-activity-pub
- https://paul.kinlan.me/adding-activity-pub-to-your-static-site/
- https://macwright.com/2022/12/09/activitypub.html
