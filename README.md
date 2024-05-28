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

## ⚡Quick Guide
| Type  | Size | Quality | Compression | Web | Mobile | Sample Rates (kHz)                                | Bit Rates (kbps)                         | Comments                                                                  |
|-------|------|---------|-------------|-----|--------|---------------------------------------------------|------------------------------------------|---------------------------------------------------------------------------|
| .aac  | 4️⃣  | 8️⃣      | Lossy       | ✅ | ✅     | 8 - 96                                            | 8 - 512                                  | iTunes                                                                    |
| .aiff | 🔟  | 🔟      | Lossless    | ❌ | ❌     | 8 - 192                                           | 1411 (CD quality), up to 4608            | Professional recording, Mac environments                                  |
| .alac | 6️⃣  | 9️⃣      | Lossless    | ❌ | ❌     | 1 - 384                                           | Up to 9216                               | Audio archiving, Apple devices                                            |
| .dsd  | 🔟  | 🔟      | Lossless    | ❌ | ❌     | 2822.4 (DSD64), 5644.8 (DSD128), 11289.6 (DSD256) | 5645, 11289, 22579                       | Super Audio CDs, professional audio                                       |
| .flac | 6️⃣  | 9️⃣      | Lossless    | ✅ | ❌     | 1 - 192                                           | Up to 9216                               | Audio archiving, high-quality listening                                   |
| .m4a  | 5️⃣  | 8️⃣/🔟  | Both        | ✅ | ✅     | 8 - 96                                            | 8 - 512 (lossy), up to 1411 (lossless)   | iTunes, Apple Music, mobile applications                                  |
| .mp2  | 3️⃣  | 6️⃣      | Lossy       | ❌ | ❌     | 16 - 48                                           | 32 - 384                                 | Broadcasting                                                              |
| .mp3  | 4️⃣  | 7️⃣      | Lossy       | ✅ | ✅     | 8 - 48                                            | 8 - 320                                  | Support globally.                                                         |
| .ogg  | 3️⃣  | 7️⃣      | Lossy       | ✅ | ✅     | 8 - 48                                            | 16 - 500                                 | Also used for game sound banks (Wwise, FMOD etc)                          |
| .opus | 2️⃣  | 8️⃣      | Lossy       | ✅ | ✅     | 8 - 48                                            | 6 - 510                                  | Not widely used. Streaming, voice over IP                                 |
| .wav  | 🔟  | 🔟      | Lossless    | ✅ | ✅     | 8 - 192                                           | 1411 (CD quality), up to 4608            | Support globally. Professional recording, high-definition media, games    |
| .wma  | 5️⃣  | 8️⃣/🔟  | Both        | ❌ | ❌     | 8 - 48                                            | 48 - 192 (lossy), up to 1536 (lossless)  | Windows                                                                   |
| .midi | 1️⃣  | 5️⃣      | 🚫         | ✅ | ❌     | 🚫                                                | 🚫                                      | Music production, electronic instruments                                  |

## 📂 File Types

### .aac
Advanced Audio Codec (AAC) is a digital audio coding standard that was designed to be the successor to the MP3 format. Developed by a consortium of companies including AT&T Bell Laboratories, Fraunhofer IIS, Dolby Laboratories, Sony Corporation, and Nokia, AAC is now part of the MPEG-2 and MPEG-4 standards. AAC offers better sound quality than MP3 at similar bit rates. It's also the default format for iTunes and Apple Music. AAC files support metadata and are widely used in web and mobile applications. 

#### Key Features
- Superior Sound Quality: Compared to MP3 at similar bit rates, AAC typically offers better sound quality. This improvement is due to more advanced compression algorithms and greater efficiency in coding techniques.
- Compression Efficiency: AAC achieves higher compression rates while maintaining audio quality, making it ideal for streaming and storage. This efficiency is particularly beneficial for mobile and online applications where bandwidth and storage space are limited.
- Broad Frequency Range: AAC supports a wider frequency range than MP3, from 8 Hz to 96 kHz, which allows it to handle both low and high-frequency sounds more effectively.
#### Technical Specifications
- Metadata: Supports Extensive Metadata ID tags.
- Channels: Supports up to 48 full-bandwidth audio channels
- Sample Rates: Supports 8 kHz to 96 kHz.
- Bit Rates: Supports 8 kbps to 320 kbps or higher, depending on the profile and application.
#### Profiles
AAC has several profiles tailored to different applications.
- AAC-LC (Low Complexity): The most commonly used profile, providing a good balance between complexity and compression efficiency.
- HE-AAC (High-Efficiency AAC): Optimized for low bit rates, often used in streaming applications.
- HE-AACv2: An extension of HE-AAC, including Parametric Stereo (PS) for even better performance at very low bit rates.
- AAC-LD (Low Delay): Designed for real-time communication applications where low latency is crucial.
- AAC-ELD (Enhanced Low Delay): Further improves on AAC-LD for high-quality, low-latency audio streaming.
#### Applications
- Music Streaming: Widely used in music streaming services such as Apple Music, YouTube, and Spotify due to its balance of sound quality and file size.
- Mobile Devices: Apple's use of AAC in iTunes has popularized the format for mobile, specifically iPhone.
- Broadcasting: Digital radio and television broadcasts often use AAC for audio due to its efficiency and high quality. The format is part of the DVB and ATSC standards.
- VoIP and Conferencing: AAC-ELD and AAC-LD profiles are used in applications where low latency is critical, such as voice over IP (VoIP) and video conferencing.
#### Advantages
- High Audio Quality at Low Bit Rates: AAC can deliver excellent audio quality even at lower bit rates, making it ideal for streaming and mobile applications where bandwidth and storage are concerns.
- Widespread Compatibility: With support across a broad range of devices and platforms, AAC is a versatile choice for digital audio.
- Advanced Features: Support for multi-channel audio and high-frequency ranges makes AAC suitable for a variety of applications beyond simple music playback.
#### Disadvantages
- Licensing Fees: Unlike some open-source codecs, AAC is patented, and using it in commercial products may require licensing fees.
- Compatibility Issues with Older Devices: Some older hardware and software may not fully support AAC, particularly more advanced profiles like HE-AAC and HE-AACv2.

### .aiff
Similar to .wav in size and quality, AIFF is a lossless format developed by Apple. It is commonly used in Mac environments for professional audio applications. It supports a wide range of sample rates and bit rates and includes metadata support.

### .alac
Apple Lossless Audio Codec is similar to FLAC but designed for use with Apple products. It provides high-quality audio without the loss associated with lossy formats, supports metadata, and is used for audio archiving and high-quality listening.

### .dsd
Direct Stream Digital is used in Super Audio CDs (SACDs) and provides extremely high-quality audio but results in very large file sizes. It supports high sample rates and bit rates, making it ideal for professional audio applications.

### .flac
This file type is smaller than .wav and is capable of high comparable quality. It is made by sampling the audio into layers. It’s a lossless codec with an open license, compatible with most digital software but is not as widely used outside of the audio industry.

### .m4a
M4A (MPEG-4 Audio) is a file format used primarily by Apple devices and applications. It can contain audio encoded with either the lossy AAC (Advanced Audio Coding) codec or the lossless ALAC (Apple Lossless Audio Codec). This format is widely used for distributing music via iTunes and Apple Music. M4A files support a range of sample rates and bit rates, and they include metadata support, making them suitable for high-quality audio playback and efficient storage.

### .mp2
MPEG-1 Audio Layer II (MP2) is a digital audio coding format that predates the more widely known MP3 format. Developed as part of the MPEG-1 standard by the Moving Picture Experts Group (MPEG), MP2 was initially designed for use in digital television broadcasting and digital radio. Although it has been largely superseded by more advanced codecs like MP3 and AAC in many applications, MP2 remains in use in specific broadcasting contexts due to its robustness and error resilience.
- #### Key Features
  - Robustness: MP2 is known for its error resilience and robustness, making it suitable for professional broadcast environments where audio quality must be maintained over potentially unreliable transmission channels.
  - Simplicity: The encoding and decoding processes for MP2 are less complex than those for MP3 and AAC, which can lead to lower computational requirements.
  - Legacy Support: Due to its early adoption in broadcasting, MP2 maintains a significant presence in certain legacy systems and infrastructures.
- #### Technical Specifications
  - Metadata: MP2 supports limited metadata compared to newer formats. It can include basic information such as track title and artist.
  - Channels: MP2 supports up to two channels (stereo).
  - Sample Rates: Commonly supports sample rates of 32 kHz, 44.1 kHz, and 48 kHz.
  - Bit Rates: Typically supports bit rates from 32 kbps to 384 kbps, with 192 kbps being common for stereo audio in broadcasting.
- #### Applications
  - Digital Broadcasting: MP2 is widely used in Digital Audio Broadcasting (DAB) and Digital Video Broadcasting (DVB). Its robustness makes it ideal for use in environments where signal integrity cannot be guaranteed.
  - Professional Audio: Some professional audio equipment and workflows still use MP2, particularly in the broadcast industry.
  - Legacy Systems: MP2 remains relevant in systems and infrastructures that were established before the widespread adoption of MP3 and AAC.
- #### Advantages
  - Robustness and Error Resilience: MP2's ability to maintain audio quality over unreliable transmission channels makes it a reliable choice for broadcasting.
  - Low Computational Requirements: The simplicity of the MP2 codec means it requires less computational power to encode and decode compared to more modern codecs.
  - Established Use in Broadcasting: MP2's longstanding use in digital radio and television broadcasting ensures its continued relevance in these fields.
- #### Disadvantages
  - Limited Audio Quality at Lower Bit Rates: MP2 does not perform as well as newer codecs like MP3 or AAC at lower bit rates, leading to inferior audio quality in some cases.
  - Limited Metadata Support: MP2's metadata capabilities are limited compared to newer formats, which can affect file organization and user experience.
  - Obsolescence in Consumer Applications: With the advent of more efficient codecs like MP3 and AAC, MP2 has become less common in consumer applications and devices.

### .mp3
This file type is smaller than .wav and is capable of good comparable quality. It is made by sampling the audio into layers – it is compatible with most digital software and is more appropriate for web and mobile applications. It is very lossy, however.
- Metadata Support: Yes, supports Extensive Metadata ID tags.
- Supported Platforms: All

### .ogg
This file type is even smaller comparatively than a .mp3 and the quality difference is negligible. It is made by sampling the audio into layers but also ignores “silence” in the sample, greatly reducing the size and processing cost. Although it is lossy and becoming slightly obsolete/less compatible for most media, it is compatible with most digital software and is widely used in web and mobile, as well as for generating sound banks for large-scale AAA game projects.

### .opus
Opus is a highly versatile and efficient lossy audio codec designed for streaming and real-time applications such as voice over IP. It offers high audio quality at low bit rates, making it ideal for bandwidth-sensitive uses. Opus supports a wide range of sample rates and bit rates, providing good quality even at lower file sizes. It also includes extensive metadata support, making it a robust choice for various audio applications.

### .wav
Large, uncompressed, and capable of higher comparable quality. It is made by sampling the audio into a waveform – as such, it is compatible with most digital software and is widely used for high-definition media. It’s a lossless codec, which means that it is stored via an algorithm that allows the original audio data to be perfectly reconstructed from the compressed data.
- Metadata Support: Yes, supports INFO chunks but limited compared to more modern formats.
- Supported Platforms: All

### .wma
Windows Media Audio, developed by Microsoft, comes in both lossy and lossless versions. It supports metadata and a wide range of sample and bit rates. While less popular today, it was widely used for streaming and downloading music.

### .midi
MIDI (Musical Instrument Digital Interface) files are unique in that they do not contain actual audio data but instead store a set of instructions for synthesizers to generate sounds. This makes MIDI files extremely small in size. They are widely used in music production and for controlling electronic musical instruments. MIDI files support metadata, including information such as tempo, instrument data, and control signals, but do not have traditional sample rates or bit rates as found in audio files.


-----------------------------------------------------------------------

## 📝 Metadata
Each audio file type has a container format or “Wrapper”, which allow more data to be embedded into a single file, usually along with metadata for identifying and further detailing those files. This often includes Metadata, such as tags, sample rate, BPM, length, midi information, loop markers, and strings such as the name of the creator and the size of the file. Sometimes, there can be even more data, such as images, and links in this metadata.
There are several types of metadata:

- #### ✅ Basic Metadata
Includes fundamental details about the audio content but may not support the full range of metadata fields available in more modern or comprehensive formats.
Basic metadata often includes:
Title: The name of the track.
Artist: The name of the artist or performer.
Album: The name of the album the track belongs to.
Year: The year the track was released or recorded.
Genre: The genre of the track (e.g., rock, classical, jazz).
Track Number: The position of the track within an album.
Duration: The length of the track.

- #### 🆔 Extensive Metadata
Extensive metadata formats include all the basic fields plus additional information. File types supported are .mp3 (with ID3 tags), .flac, .m4a, and .ogg, allowing for a richer and more informative tagging system.
These often include:
Album Artwork: Images associated with the album or track.
Lyrics: The words to the song.
Composer: Information about the composer of the track.
Conductor: Information about the conductor (for classical music).
Bit Rate: Information about the bit rate of the file.
Sample Rate: Information about the sample rate of the file.
Comment: Additional notes or comments about the track.
User-Defined Tags: Custom tags defined by the user.

- #### ⚠️ Limited or No Metadata Support
As described - the file does not support metadata for either security, size, or legacy restrictions.


-----------------------------------------------------------------------

## 📻 Software Audio File Requirements
Certain software only supports usage of certain audio file types.
Here are the files I'd recommend using with each software.

| Software | Supported Files |
|----------|-----------------|
| <a href = "https://docs.unrealengine.com/5.3/en-US/"> <img align="left" img height="40" img width="40" src="https://cdn.simpleicons.org/unrealengine/white"> </a>  | .wav 16-bit PCM @ 44100Hz |
| <a href = "https://docs.unity.com/"> <img align="left" img height="40" img width="40" src="https://cdn.simpleicons.org/unity/white"> </a>                          | .wav, .ogg, .mp3 |
| <a href = "https://www.godot.com/"> <img align="left" img height="40" img width="40" src="https://cdn.simpleicons.org/godotengine"> </a>                           | .wav, .ogg, .mp3 |
| <a href = "https://gamemaker.io/"> <img align="left" img height="40" img width="40" src="https://cdn.simpleicons.org/gamemaker"> </a>                             | .wav, .ogg, .mp3 |
| <a href = "hhttps://www.audiokinetic.com/en/"> <img align="left" img height="40" img width="40" src="https://cdn.simpleicons.org/wwise/white"> </a>                | .wav 24-bit PCM @ 48000Hz      |
| RPG Maker                                                                                                                                                          | .ogg, .m4a (for Mac/Safari)    |
| <a href = ""> <img align="left" img height="40" img width="40" src="https://cdn.simpleicons.org/firefoxbrowser">                                                   | .wav, .mp3, .ogg, .flac, .aac, .opus, .m4a, .midi   |
| <a href = ""> <img align="left" img height="40" img width="40" src="https://cdn.simpleicons.org/googlechrome">                                                     | .wav, .mp3, .ogg, .flac, .aac, .opus, .m4a, .midi   |
| <a href = ""> <img align="left" img height="40" img width="40" src="https://cdn.simpleicons.org/microsoftedge">                                                    | .wav, .mp3, .ogg, .flac, .aac, .opus, .m4a, .midi   |
| <a href = ""> <img align="left" img height="40" img width="40" src="https://cdn.simpleicons.org/safari">                                                           | .wav, .mp3, .aiff, .alac, .aac, .m4a  |
| <a href = ""> <img align="left" img height="40" img width="40" src="https://cdn.simpleicons.org/internetexplorer">                                                 | .wav, .mp3, .wma (use plugins for additional types)    |

-----------------------------------------------------------------------
