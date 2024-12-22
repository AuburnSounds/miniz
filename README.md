# Miniz

**This is the port, see original library here: https://github.com/richgel999/miniz**.

Miniz is a lossless, high performance data compression library in a single source file that implements the zlib (RFC 1950) and Deflate (RFC 1951) compressed data format specification standards. It supports the most commonly used functions exported by the zlib library, but is a completely independent implementation so zlib's licensing requirements do not apply. Miniz also contains simple to use functions for writing .PNG format image files and reading/writing/appending .ZIP format archives. Miniz's compression speed has been tuned to be comparable to zlib's, and it also has a specialized real-time compressor function designed to compare well against fastlz/minilzo.


## Changes

- Not all functions were ported. Basically the DEFLATE codec is there but no `.zip` support.
- Was a bit modified to decode Apple's PNG like in stbz from `stb_image.h`.