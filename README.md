![image](https://github.com/JDSherbert/Audio-File-Guide/assets/43964243/5e8b9ed7-d3ef-4c3a-922e-419ba0e60bce)

# Audio File Guide

<!-- Header Start -->

<img align="right" alt="Stars Badge" src="https://img.shields.io/github/stars/jdsherbert/Audio-File-Guide?label=%E2%AD%90"/>
<img align="right" alt="Forks Badge" src="https://img.shields.io/github/forks/jdsherbert/Audio-File-Guide?label=%F0%9F%8D%B4"/>
<img align="right" alt="Watchers Badge" src="https://img.shields.io/github/watchers/jdsherbert/Audio-File-Guide?label=%F0%9F%91%81%EF%B8%8F"/>
<img align="right" alt="Issues Badge" src="https://img.shields.io/github/issues/jdsherbert/Audio-File-Guide?label=%E2%9A%A0%EF%B8%8F"/>
<img align="right" src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FJDSherbert%2FAudio-File-Guide%2Fhit-counter%2FREADME&count_bg=%2379C83D&title_bg=%23555555&labelColor=0E1128&title=🔍&style=for-the-badge">
<!-- Header End --> 

-----------------------------------------------------------------------

<a href=""> 
  <img align="left" alt="Audio Processing" src="https://img.shields.io/badge/Audio%20Processing-black?style=for-the-badge&logo=audacity&logoColor=white&color=black&labelColor=black"> </a>
  
<br></br>

-----------------------------------------------------------------------
## Overview
As an audio engineer, understanding the various audio file formats is crucial to ensuring the best quality and compatibility for your projects. Audio file types differ not only in their quality and file size but also in their suitability for different applications, from casual listening to professional recording, production, transporting, editing, and "lossy-ness". I'll be approaching each file format from a Games Industry perspective and discussing their unique characteristics, advantages, and potential drawbacks. Whether you're mastering tracks in a studio, encoding audio for streaming, or archiving a music collection, selecting the right file format can make a significant difference in your workflow and the listening experience. 

Let's dive into the details of each format, examining how they compress audio data, the quality they offer, and their typical use cases in the audio industry.


-----------------------------------------------------------------------

## File Types
Each audio file type has a container format or “Wrapper”, which allow more data to be embedded into a single file, usually along with metadata for identifying and further detailing those files. This often includes Metadata, such as tags, sample rate, BPM, length, midi information, loop markers, and strings such as the name of the creator and the size of the file. Sometimes, there can be even more data, such as images, and links in this metadata.

## Quick Guide
| Type  | Size | Quality | Compression | Common Uses                                   | Sample Rates (kHz)       | Bit Rates (kbps)          |
|-------|------|---------|-------------|-----------------------------------------------|--------------------------|---------------------------|
| .wav  | 10   | 10      | Lossless    | Professional recording, high-definition media | 8 - 192                  | 1411 (CD quality), up to 4608 |
| .mp3  | 4    | 7       | Lossy       | Web, mobile applications                      | 8 - 48                   | 8 - 320                   |
| .ogg  | 3    | 7       | Lossy       | Web, mobile, game sound banks                 | 8 - 48                   | 16 - 500                  |
| .flac | 6    | 9       | Lossless    | Audio archiving, high-quality listening       | 1 - 192                  | Up to 9216                |
| .aiff | 10   | 10      | Lossless    | Professional recording, Mac environments      | 8 - 192                  | 1411 (CD quality), up to 4608 |
| .aac  | 4    | 8       | Lossy       | Web, mobile applications, iTunes              | 8 - 96                   | 8 - 512                   |
| .wma  | 5    | 8 / 10  | Both        | Web, mobile applications, Windows             | 8 - 48                   | 48 - 192 (lossy), up to 1536 (lossless) |
| .alac | 6    | 9       | Lossless    | Audio archiving, Apple devices                | 1 - 384                  | Up to 9216                |
| .dsd  | 10   | 10      | Lossless    | Super Audio CDs, professional audio           | 2822.4 (DSD64), 5644.8 (DSD128), 11289.6 (DSD256) | 5645, 11289, 22579       |
| .mp2  | 3    | 6       | Lossy       | Broadcasting                                  | 16 - 48                  | 32 - 384                  |
| .opus | 2    | 8       | Lossy       | Streaming, voice over IP                      | 8 - 48                   | 6 - 510                   |
| .m4a  | 5    | 8 / 10  | Both        | iTunes, Apple Music, mobile applications      | 8 - 96                   | 8 - 512 (lossy), up to 1411 (lossless)    |
| .midi | 1    | 5       | None        | Music production, electronic instruments      | N/A                      | N/A                       |

### .wav
Large, uncompressed, and capable of higher comparable quality. It is made by sampling the audio into a waveform – as such, it is compatible with most digital software and is widely used for high-definition media. It’s a lossless codec, which means that it is stored via an algorithm that allows the original audio data to be perfectly reconstructed from the compressed data.

### .mp3
This file type is smaller than .wav and is capable of good comparable quality. It is made by sampling the audio into layers – it is compatible with most digital software and is more appropriate for web and mobile applications. It is very lossy, however.

### .ogg
This file type is even smaller comparatively than a .mp3 and the quality difference is negligible. It is made by sampling the audio into layers but also ignores “silence” in the sample, greatly reducing the size and processing cost. Although it is lossy and becoming slightly obsolete/less compatible for most media, it is compatible with most digital software and is widely used in web and mobile, as well as for generating sound banks for large-scale AAA game projects.

### .flac
This file type is smaller than .wav and is capable of high comparable quality. It is made by sampling the audio into layers. It’s a lossless codec with an open license, compatible with most digital software but is not as widely used outside of the audio industry.

### .aiff
Similar to .wav in size and quality, AIFF is a lossless format developed by Apple. It is commonly used in Mac environments for professional audio applications. It supports a wide range of sample rates and bit rates and includes metadata support.

### .aac
Advanced Audio Coding offers better sound quality than MP3 at similar bit rates. It is the default format for iTunes and Apple Music. AAC files support metadata and are widely used in web and mobile applications.

### .wma
Windows Media Audio, developed by Microsoft, comes in both lossy and lossless versions. It supports metadata and a wide range of sample and bit rates. While less popular today, it was widely used for streaming and downloading music.

### .alac
Apple Lossless Audio Codec is similar to FLAC but designed for use with Apple products. It provides high-quality audio without the loss associated with lossy formats, supports metadata, and is used for audio archiving and high-quality listening.

### .dsd
Direct Stream Digital is used in Super Audio CDs (SACDs) and provides extremely high-quality audio but results in very large file sizes. It supports high sample rates and bit rates, making it ideal for professional audio applications.

### .mp2
MPEG Layer II is mainly used for broadcasting due to its robustness and good audio quality at lower bit rates. It supports metadata and a range of sample rates and bit rates, though it is less common today.

### .opus
Opus is a highly versatile and efficient lossy audio codec designed for streaming and real-time applications such as voice over IP. It offers high audio quality at low bit rates, making it ideal for bandwidth-sensitive uses. Opus supports a wide range of sample rates and bit rates, providing good quality even at lower file sizes. It also includes extensive metadata support, making it a robust choice for various audio applications.

### .m4a
M4A (MPEG-4 Audio) is a file format used primarily by Apple devices and applications. It can contain audio encoded with either the lossy AAC (Advanced Audio Coding) codec or the lossless ALAC (Apple Lossless Audio Codec). This format is widely used for distributing music via iTunes and Apple Music. M4A files support a range of sample rates and bit rates, and they include metadata support, making them suitable for high-quality audio playback and efficient storage.

### .midi
MIDI (Musical Instrument Digital Interface) files are unique in that they do not contain actual audio data but instead store a set of instructions for synthesizers to generate sounds. This makes MIDI files extremely small in size. They are widely used in music production and for controlling electronic musical instruments. MIDI files support metadata, including information such as tempo, instrument data, and control signals, but do not have traditional sample rates or bit rates as found in audio files.



-----------------------------------------------------------------------
