# 01 - Media Embed Checklist

## Goal

Build usable native video and audio players with fallbacks and text alternatives.

## Tasks

1. Add `controls` and the supplied poster to the video.
2. Add both WebM and MP4 sources with correct MIME types.
3. Add the English captions track and make it the default.
4. Add a fallback link that downloads the MP4.
5. Add the MP3 source and controls to the audio player.
6. Add an audio fallback download link.
7. Link the video player to the supplied transcript.
8. Do not autoplay either player.

## Completion Check

Test controls with the keyboard, enable captions, and verify that every local
file request returns successfully in the Network panel.
