# Psyche

A 3D graph representation of a personality profile

## Dependencies

* [Cloudvisio](http://github.com/makesites/cloudvisio)
* [PN:OI API](http://pnoi.net/docs/api) for realtime intellect updates

## Install

```
$ npm install psyche
```

## Usage

To present a personality, a signature of it's main attributes is required. This signature can be created manually or ingested from an online source as a JSON data file. The schema of the JSON is as defined by [PN:OI](http://pnoi.net/docs/pneuma) for a Pneuma construct.

```
const psyche = require('psyche');

var pneuma = {...};

// load attributes

psyche.load( pneuma );

...

// output

psyche.render();

```


## Credits

Initiated by Makis Tracend ( [@tracend](http://tracend.me/) )

Distributed through [K&D Interactive](http://kdi.co/)

Released under the [Creative Commons BY-NC-ND license](http://creativecommons.org/licenses/by-nc-nd/3.0/)
