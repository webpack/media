## Creating SVGs

Sketch exports SVGs that use CSS transforms. Unfortunately, these SVGs
are sometimes rendered poorly in some browsers. In order to avoid this,
please repeat following steps every time a new SVG is exported:

- Open in Illustrator
- Remove all groups
- Save
- Repeat for all vectors
- Run cd `logo && svgo -f .`

See also [#4](https://github.com/webpack/media/pull/4)
