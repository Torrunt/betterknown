# betterknown

I wrote [wellknown](https://github.com/mapbox/wellknown), a WKT parser and stringifier,
eons ago. It's still sort of popular but nobody maintained it after I left Mapbox.

There's [wkx](https://github.com/cschwarz/wkx), which is stricter and honestly
has a better parser, plus supports WKB, but it's also abandoned and has some drawbacks -
no TypeScript, somewhat idiosyncratic code, and the bundle size is larger than it
needs to be because it brings in browserify shims.

This project aims to be the combination of the two projects. Lightweight like
wellknown, strict and correct like wkx, plus with the 2022 energy of supporting
TypeScript from day one.

- 100% TypeScript
- **No dependencies** - tiny bundle
- Parse WKT to GeoJSON, stringify GeoJSON to WKT
