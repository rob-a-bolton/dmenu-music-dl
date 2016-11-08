About
=====

This script allows you to download music from any site that works with youtube-dl
and id3 tag it.

Text input is done via dmenu.
Thumbnails are saved where possible.
The default music directory used is *~/music*,
Should you wish to change this (e.g. if you use the default XDG *~/Music* dir) then modify the
variables at the top of both scripts.

Dependencies:

 - mutagen (provides mid3v2, available on pip)
 - youtube-dl (also available on pip)
 - ffmpeg (converts to mp3)
 - xclip or xsel (optional, pastes current clipboard selection as default input url)
 - notify-send (part of libnotify, sends notifications when either script is complete (if you are in an X session))

