# AVCodec 
> NOTE: Doesn't compile — uses deprecated API.

An object for encoding and decoding audio and video streams.

When an input stream containing audio data is opened, the following slots will be set:
```Io
audioChannels
audioSampleRate
audioBitRate
audioDuration
audioFrameCount
```

When an input stream containing video data is opened, the following slots will be set:

```Io
framePeriod
videoDuration
videoFrameCount
```

# Installation
`ffmpeg` should be installed and foundable in your system. Then:
```
eerie install https://github.com/IoLanguage/AVCodec.git
```
