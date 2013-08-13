HLS Probe Utility
=================

Utility to detect errors in HTTP Live Streams (Apple HLS).
It may be used regular monitoring tool and mediaserver stress testing.
Features are:

 * parse M3U8-playlists (variant and single-bitrate playlists supported)
 * detect bad playlists format (empty playlists, incorrect chunk durations)
 * check HTTP response statuses and webserver timeouts

Planned features:

 * probe chunks with `mediainfo` utility (from libav)

This utility can't be used for HLS playback.

This Python version are maintained but development moved to version on Go language:
https://github.com/grafov/hlsprobe2

Install
-------

First install dependencies:

`pip install m3u8`

`pip install PyYAML`

Get repo, cd to it and copy hlsproberc-sample to ~/.hlsproberc. Edit it for your needs.

`./hlsprobe`

Similar projects
----------------

 * https://code.google.com/p/hls-player
 * https://github.com/brookemckim/hlspider

Project status
--------------

[![Is maintained?](http://stillmaintained.com/grafov/hlsprobe.png)](http://stillmaintained.com/grafov/hlsprobe)
