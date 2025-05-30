# chafa

> Image printing in the terminal.
> See also: `catimg`, `pixterm`.
> More information: <https://hpjansson.org/chafa/man>.

- Render an image directly in the terminal:

`chafa {{path/to/file}}`

- Render an image with 24-bit color:

`chafa {{[-c|--colors]}} full {{path/to/file}}`

- Improve image rendering with small color palettes using dithering:

`chafa {{[-c|--colors]}} 16 --dither ordered {{path/to/file}}`

- Render an image, making it appear pixelated:

`chafa --symbols vhalf {{path/to/file}}`

- Render a monochrome image with only braille characters:

`chafa {{[-c|--colors]}} none --symbols braille {{path/to/file}}`
