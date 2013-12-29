Looper - Rhythmbox plugin
=========================

Loop part of the song in Rhythmbox.

Screenshots
-----------

![](https://github.com/kingd/looper/looper.png)

## Install

Copy looper folder into your local `rhythmbox/plugins` directory. On Debian/Ubuntu 
this is `~/.local/share/rhythmbox/plugins`. Following commands will install for those systems:

    git clone https://github.com/kingd/looper
    mv looper/looper ~/.local/share/rhythmbox/plugins
    rm -rf looper

## Known Issues

`Crossfade between tracks` option changes to next or previous song while the
current time is near the edges of the song. Thats why it will be temporary
disabled when the Looper is in control of the playback. 

Rhythmbox also changes to next song if the song is less than 3 seconds before the end.
Therefore those last 3 seconds wont be available for looping.

Currently only tested on Rhythmbox 2.97.

## TODO

Try it on Rhythmbox 3+

## Author

Ivan Augustinović https://github.com/kingd
