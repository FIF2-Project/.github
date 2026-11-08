## FIF2: a free reboot of the Fractal Image Format

FIF2 is an open file format for fractal images, with a complete specification and
a reference implementation in source code. It uses the method of the 1990s
fractal formats, which were closed, patented and are no longer supported, and
makes it freely usable again.

Fractal images have properties no mainstream format offers:

- **Resolution independence.** A picture can be decoded larger than it was stored,
  rendering new detail instead of resampling pixels.
- **Progressive by nature.** Every beginning of a file is a complete picture.
- **Random access.** Regions decode on their own.

### Repositories

| Repository | Contents |
| --- | --- |
| [**libfif**](https://github.com/FIF2-Project/libfif) | reference encoder and decoder (C library) and the `fif` command-line tool, with [downloads](https://github.com/FIF2-Project/libfif/releases/latest) for Windows and macOS |

### Learn more

- [**The FIF2 format** (fif2.org)](https://fif2.org): why a new open format, the specification, documentation
- [**What is fractal image compression?** (fractalimagecompression.com)](https://www.fractalimagecompression.com)

<sub>libfif and fif: Oskar Behzadpour · FIF2 format: Rezar Behzad</sub>
