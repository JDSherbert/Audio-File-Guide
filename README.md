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
| File Type | Size       | Quality          | Compression Type | Common Uses                            | Notes                                           |
|-----------|------------|------------------|------------------|----------------------------------------|-------------------------------------------------|
| .wav      | Large      | High             | Lossless         | Professional recording, high-definition media | Compatible with most digital software, uncompressed |
| .mp3      | Small      | Good             | Lossy            | Web, mobile applications                | Widely compatible, smaller size but lossy       |
| .ogg      | Very Small | Good             | Lossy            | Web, mobile, game sound banks           | Less common now, but efficient in size          |
| .flac     | Medium     | Very High        | Lossless         | Audio archiving, high-quality listening | Open license, not as widely used outside audio industry |


### .wav
Large, uncompressed, and capable of higher comparable quality. It is made by sampling the audio into a waveform – as such, it is compatible with most digital software and is widely used for high definition media. It’s a lossless codec, which means that it is stored via an algorithm that allows the original audio data to be perfectly reconstructed from the compressed data.

### .mp3 
This file type is smaller than .wav and is capable of good comparable quality. It is made by sampling the audio into layers – it is compatible with most digital software and is more appropriate for web and mobile applications. It is very lossy, however.

### .ogg
This file type is even smaller comparatively than a .mp3 and the quality difference is negligible. It is made by sampling the audio into layers, but also ignores “silence” in the sample, greatly reducing the size and processing cost – although it is lossy, and is becoming slightly obsolete/less compatible for most media, it is compatible with most digital software and is widely used in web and mobile, as well as for generating sound banks for large scale AAA game projects.

### .flac 
This file type is smaller than .wav and is capable of high comparable quality. It is made by sampling the audio into layers – it’s a lossless codec with an open licence, compatible with most digital software but is not as widely used outside of the audio industry.




-----------------------------------------------------------------------
