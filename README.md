# brand

Brand assets of [go-theca](https://github.com/go-theca): svg, png, jpg, ico, icns,
avatar and social banner, in colour, white and black variants.

The files are the output of the fleet's brand pipeline (`logos/brandgen`) from the
organisation glyph. They are not edited by hand. `go test ./...` checks that the kit
is whole: every file present, the SVGs parse, the rasters decode at the size their
directory names.

## Third-party glyph

The white line glyph is the "safe" icon of [Iconoir](https://github.com/iconoir-icons/iconoir)
(`icons/regular/safe.svg` at 39834e3), MIT licence, Copyright (c) 2021 Luca Burgio.
