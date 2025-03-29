# HC Media Streaming Service - Video to DASH Converter

## Overview

This Python script provides a comprehensive solution for downloading videos from various sources, converting them to DASH format, and creating a streaming-ready HTML player with optional TMDB metadata integration. The service supports multiple video platforms and direct file downloads, making it versatile for various use cases.

## Key Features

- **Multi-Source Video Downloading**: Supports YouTube, Vimeo, Dailymotion, Twitch, Facebook, Instagram, TikTok, Twitter, Google Drive, direct file links, and M3U8 streams
- **DASH Conversion**: Converts videos to MPEG-DASH format for adaptive streaming
- **Audio/Subtitle Extraction**: Automatically extracts and processes multiple audio and subtitle tracks
- **TMDB Integration**: Optionally fetches rich metadata for movies and TV shows
- **SFTP Upload**: Automatically uploads processed files to an SFTP server
- **Responsive HTML Player**: Generates a Netflix-style player with JWPlayer integration

## Technical Details

### Supported Platforms
- YouTube, Vimeo, Dailymotion, Twitch
- Facebook, Instagram, TikTok, Twitter
- Direct MP4/MKV/MOV/WebM URLs
- M3U8 streams (HLS)
- Google Drive links

### Codec Support
- Video: H.264, HEVC/H.265 (automatically converted to H.264)
- Audio: AAC, E-AC3 (converted to AAC), MP3, Opus, and more
- Subtitles: Extracts and converts to WebVTT format

### Language Support
- Comprehensive language mapping for 100+ languages
- Automatic language detection from video metadata

## Demo Links

Check out these live examples of processed videos:

1. [Sample Video 1](https://dev-hcmedia.pantheonsite.io/dash/4QmYdB/stream.html)
2. [Sample Video 2](https://dev-hcmedia.pantheonsite.io/dash/D9RBUQ/stream.html)

## Pricing

Affordable video processing service:
- **Only ₹5 per video conversion**
- Custom solutions available for high-volume needs

## Contact

For conversions or custom solutions:
- Telegram: [@awshcmedia_bot](https://telegram.me/awshcmedia_bot)

## Customization Options

We offer white-label solutions with:
- Your own domain setup
- SFTP/FTP server integration
- Custom branding and player skins
- API access for automated processing

## Requirements

To run this script locally, you'll need:
- Python 3.6+
- FFmpeg installed and in PATH
- yt-dlp
- Paramiko (for SFTP)
- Other dependencies listed in the script

## Usage

1. Run the script with `python n.py`
2. Enter the video URL when prompted
3. Optionally search for TMDB metadata
4. The script will process the video and provide streaming links

## Note

This service is provided by HC Media Streaming Service. For commercial use or high-volume processing, please contact us for customized solutions.
