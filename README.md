# Lagrange fontpacks for U.S. Graphics fonts

I wanted to use fonts from [U.S. Graphics][] in [Lagrange][]. Because I wanted better reproducibility than what I’d get from just relying on my shell’s history, I made a Makefile to capture the process, automate cleaning, and make it easier to make more than one fontpack.

Simply dig out your `.otf` font files, put them in the corresponding directory, and then run `make` at the command line to generate the `.fontpack` file. Then drag the `.fontpack` file onto your Lagrange window to install it.

You may be interested in this sort of thing, but for MB Type fonts. In that case, visit <https://github.com/adiabatic/lagrange-mb-type-fontpacks>.

## Obvious questions

### Where are the font files?

They’re not free, so you’ll have to buy them at <https://berkeleygraphics.com/>.

Feel free to choose whatever style of 0 and 7 you want, along with whatever ligature settings you want.

### OK, I bought the font. He gave me a lot of files. What do I do with them?

You’ll want to gather up the OTF fonts in the `OTF` directory. Once you’ve located the `.otf` files for the fonts you want, copy the `.otf` files to the `berkeley-mono` directory so the `.otf` files are alongside the `fontpack.ini` file.

Then run `make`.

## License

[CC0][] for my stuff. Not for the fonts themselves, obviously.

[u.s. graphics]: https://berkeleygraphics.com/
[lagrange]: https://gmi.skyjake.fi/lagrange/
[cc0]: LICENSE.md
