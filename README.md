Pythonista Scripts
=====

This is a list of my personal [Pythonista] scripts. I've uploaded them here mostly for personal reference and backup, but also on the off chance someone finds them useful.

DraftLink.py
------
Drafts a Markdown text file from a URL passed with this bookmarklet:
    
     javascript:window.location='pythonista://DraftLink?action=run&argv='+encodeURIComponent(document.location.href)+'&argv='+encodeURIComponent(document.title);

and can also include a block quote from copied text on the clipboard. The file is uploaded to a specified path on Dropbox, and then opened in Nebulous Notes for additional commentary. The `dropboxlogin.py` script handles the Dropbox requests. This DropBox module was taken from Pythonista creator OMZ's [post on the Pythonista forums].

PySky.py
-----
Mimics text part of my [PySky] script by telling you the precipitation currently, in the next hour, the following 3 hours, and next 24 hours.

Twitter2Tweetbot.py
------
A modification of Federico Viticci's script for [converting Twitter.com URLs to Tweetbot Links] with the additional abilities to both work as a bookmarklet and open a user profile, not just a specific tweet, in Tweetbot.

ImageResize.py
-----
An adaptation of an image resizing script by [MacDrfiter]. Image sizes and paths have been modified so they work with [jayhickey.com], my blog.

[jayhickey.com]:http://jayhickey.com
[Pythonista]:https://itunes.apple.com/us/app/pythonista/id528579881?mt=8&ign-mpt=uo%3D4
[MacDrfiter]:http://www.macdrifter.com/2012/11/the-power-of-pythonista-12.html
[converting Twitter.com URLs to Tweetbot Links]:http://www.macstories.net/tutorials/convert-twitter-com-urls-to-tweetbot-links/
[PySky]:https://github.com/jayhickey/PySky
[post on the Pythonista forums]:http://omz-software.com/pythonista/forums/discussion/10/using-the-dropbox-module#Item_3