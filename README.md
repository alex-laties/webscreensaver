tumblrtv-webscreensaver
==============

A screen hack which uses WebKit and works with XScreensaver to display TumblrTV!

dependencies
------------

 * python 2.7
 * pywebkitgtk
 * pygtk (gtk 2)
 * xscreensaver

install
-------

Copy `webscreensaver` into `/usr/lib/xscreensaver` and then edit `~/.xscreensaver`:

    programs:
                  webscreensaver                  \n\

You can configure `webscreensaver` with a list of tags to select either by using the `-tags` option in `~/.xscreensaver` (i.e. `-tags hello,goodbye,thirdtag` or by listing tags in `~/.tags`:
```
hello
goodbye
thirdtag
```


`webscreensaver` will always choose a random tag from the union of command line and config file tags.
Otherwise it will choose a random one.
