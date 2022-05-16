# rofi-buku
rofi frontend for buku bookmarks manager

## Features
* Adding bookmarks with tags
* Editing URLs and tags inline
* Deleting bookmarks
* Open URLs

## Dependencies
* gawk
* sed
* [buku](https://github.com/jarun/buku)
* rofi (https://github.com/DaveDavenport/rofi)
* bash

## Fork
It's a fork of the [knatsakis](https://github.com/knatsakis/rofi-buku) and [roomcays](https://github.com/roomcays/rofi-buku). Those scripts are invalid with:
* buku 4.6 - problem with parsing `buku: waiting for input (unexpected? try --nostdin)` 
* rofi 1.7.3 - new configuration format (width)

I've also changed the configuration and menu.
