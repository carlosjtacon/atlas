# atlas.carlosjtacon.com

- Different pages:
    - `globe.html` - 3D globe view, rendered with three.js with 1. pins that show different trips coordinates and 2. connection lines that follow the personal timeline steps.
    - `map.html` - 2D vector map minimal color theme with all the tracks displayed and framed in a bounding square.
    - `who/carlos.html` - Show person data, draw timeline and also add trips on it (two different levels in the timeline).
    - `timeline/alcala-1994.html` - Maybe can do a article view page for longer format text.
    - `trip/snowdonia.html` - Show trip metadata and article.


- Person data model - `carlos.json`
```json
{
    "name": "Carlos",
    "timeline": [
        {
            "where": {
                "name": "Alcala de Henares",
                "coordinates": [672.89, -679.90]
            },
            "when": 1994-05-03,
            "what": "Born. Did proper children things. Watched Star Wars in VHS",
            "text": "alcala-1994.md"
        },
        {
            "where": "Viborg",
            "when": 2018-09-10,
            "what": "Studied in The Animation Workshop"
        }
    ],
    "trips": ???? Maybe we need to link trips here
}
```

- Trip data model - `snowdonia.json`
```json
{
    "who": [
        "Carlos",
        "Alix", 
        "Mario", 
        "Evangelos"
    ],
    "when": {
        "start": 2024-10-03,  
        "end": 2024-11-06
    },
    "where": {
        "from": "London",
        "name": "Snowdonia",
        "coordinates": [907.70, -930.87]
    },
    "what" : "Hiking",
    "how": [
        "Train",
        "Walk"
    ],
    "backdrop": "snowdonia.jpg",
    "track": "snowdonia.gpx",
    "text": "snowdonia.md"
}
```


#### Resources to (maybe) use

- https://globe.gl
- https://tilemaker.org
- https://protomaps.com
- http://download.geofabrik.de
- https://maplibre.org/maplibre-gl-js
- https://leafletjs.com
- http://mpetazzoni.github.io/leaflet-gpx/
- https://github.com/mapbox/togeojson
