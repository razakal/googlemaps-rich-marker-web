RichMarker – A Google Maps JavaScript API utility library
==============

A library for using arbitrary DOM elements as map markers in the Google Maps JavaScript API v3.
![Analytics](https://maps-ga-beacon.appspot.com/UA-12846745-20/js-rich-marker/readme?pixel)

[Reference documentation](https://googlemaps.github.io/js-rich-marker/reference.html)

Migrated from the [Google Maps JavaScript API utility libraries on Google Code](https://code.google.com/p/google-maps-utility-library-v3/).

## Live Demo

[![RichMarker Screenshot](https://googlemaps.github.io/js-rich-marker/screenshot.jpg)](https://googlemaps.github.io/js-rich-marker/examples/richmarker.html)

[Example page](https://googlemaps.github.io/js-rich-marker/examples/richmarker.html)

## Additional Notes for the Springlab fork of this project

We forked the base version of RichMarker for two reasons:
 
1. To provide the code in the form of an ES6 module
2. Make the definition of the `RichMarker` and `RichMarkerPosition`
   objects lazy in order to simplify usage with tools like Webpack
   and Browserify
   
As such, please note that if you intend to use this module in an
environment without proper support for ES6 and ES6 modules you will 
need to transpile using a tool like [BabelJS](https://babeljs.io/).

## Contributing

Want to contribute? Check out the [contributing guide](CONTRIBUTING.md)!

## License

Copyright 2014 Google Inc. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
