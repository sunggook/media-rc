# Record user capture stream by using MediaRecorder API.

The code here is forked from https://github.com/webrtc/samples/tree/gh-pages/src/content/getusermedia/record.

It is created for testing MP4 muxer that works on both of Chromium and Safari browsers.

It has changes from the origin webrtc samples.
- It passes specifici sample rate for getUserMedia.
- It allows download MP4 file with .mp4 extension.
