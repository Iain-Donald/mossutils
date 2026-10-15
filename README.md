# mossutils
Utility collection for Moss Linux. 

## Map

### Original utils, before dependency consolidation and ln/arg linking. 

Where and how they are used is not yet specified. 

#### Lossless compression, general. 
- [LZ4](https://lz4.org/)
- [ZSTD](https://facebook.github.io/zstd/)
- [XZ](https://tukaani.org/xz/)

#### Lossless compression, text and web.
- Brotli

#### // Audio/Video

#### AV container formats
- Ogg (A)
- MP4 (V)
- M4A (A)
- MKV (V)
- WebM (V)

#### Lossless compression/codec, audio.
- Free Lossless Audio Codec ([FLAC](https://xiph.org/flac/))
- Waveform Audio File Format (WAV)
- Broadcast Wave Format (BWF)

#### Lossy compression/codec, audio. 
- Opus
- AAC
- MP3

#### Image formats <L = lossy | LL = lossless> <bit_depth>
- TIFF L+LL/1|8|16|32
- PNG LL/8
- [WebP](https://developers.google.com/speed/webp/docs/cwebp) L+LL/8
- [AVIF](https://aomediacodec.github.io/av1-avif/) L+LL/8|10|12
- JPEG L/8

