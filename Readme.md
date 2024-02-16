# streamdl
A small Python tool for downloading partitioned video streams from a CDN by reading the m3u8 file and 
combining the parts of all tracks (video, audio, subtitles) into one mkv file using FFmpeg.
## Table of Contents
- [Details](#section-1)
- []()
- [Getting your Tokens](##getting-your-tokens)
## Details
To download from a CDN, you most likely need access tokens that are generated in some kind of 
authentication process. For example, if the video that you want to download is locked behind a 
paywall and access is tied to account credentials, the application responsible for playing the video will 
somehow get this token for you and use it to download the video parts. For more information about the access tokens, 
read the [Tokens](##getting-your-tokens) section.
## Getting your Tokens