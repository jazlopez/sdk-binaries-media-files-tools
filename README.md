# sdk-binaries-media-files-tools
Binary Backups of C++ tools for MP4, DASH, HLS, CMAF SDK formats

| binary file |  |
| --- | --- |
| mp4info |	displays high level info about an MP4 file, including all tracks and codec details|
| mp4dump	| displays the entire atom/box structure of an MP4 file|
| mp4edit | 	add/insert/remove/replace atom/box items of an MP4 file|
| mp4extract|	extracts an atom/box from an MP4 file|
| mp4encrypt	|encrypts an MP4 file (multiple encryption schemes are supported)|
| mp4decrypt	|decrypts an MP4 file (multiple encryption schemes are supported)|
| mp4dcfpackager	|encrypts a media file into an OMA DCF file|
| mp4compact	| converts stsz tables into stz2 tables to create more compact MP4 files|
| mp4fragment	| creates a fragmented MP4 file from a non-fragmented one.|
| mp4split	| splits a fragmented MP4 file into discrete files|
| mp4tag	| show/edit MP4 metadata (iTunes-style and others)|
| mp4mux	| multiplexes one or more elementary streams (H264, AAC) into an MP4 file|
| mp42aac	| extract a raw AAC elementary stream from an MP4 file|
| mp42avc	| extract a raw AVC/H.264 elementary stream from an MP4 file|
| mp42hevc	| extract a raw AVC/H.264 elementary stream from an MP4 file|
| mp42hls	| converts an MP4 file to an HLS (HTTP Live Streaming) presentation, including the generation of the segments and .m3u8 playlist as well as AES-128 and SAMPLE-AES (for FairPlay) encryption. This can be used as a replacement for Apple’s mediafilesegmenter tool.|
| mp42ts	| converts an MP4 file to an MPEG2-TS file.|
| mp4dash	| creates an MPEG DASH output from one or more MP4 files, including encryption.|
| mp4dashclone	|creates a local clone of a remote or local MPEG DASH presentation, optionally encrypting the segments as they are cloned.|
| mp4hls	| creates a multi-bitrate HLS master playlist from one or more MP4 files, including support for encryption and I-frame-only playlists. This can be used as a replacement for Apple’s variantplaylistcreator tool.|
