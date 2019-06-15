# lv-goldenage lyp package

This is a packaging of the goldenage font packages and the lilyjazz stylesheet for use with the `lyp` package manager.

Most of the contents is just a rearrangement of Steve Lacy's (@slacy) https://github.com/OpenLilyPondFonts/lv-goldenage repository (which itself is based on [Abraham Lee](mailto:tisimst.lilypond@gmail.com)'s music font and lilypond work, Donald Rice's text fonts) to conform to `lyp` packing standards.

The only added files are:

* `package.ly`, the `lyp` packaging root.
* `jazzchords_test.ly`, a test sheet for a wide variety of jazz chords.
* `morejazz.ily`, a number of tweaks to the chord name display, notably
   * Using a triangle instead of "M" for major 7th chords.
   * Adding a few more exotic chord combinations.
   * Defining stacked alterations in a way that is more robust to font size variations.

To restore the chord naming in the original package, add `\set chordNameExceptions = #JazzChords` in your file.

GoldenAgeText and GoldenAgeTitle were created and copyrighted (c) 1996 by Donald Rice.