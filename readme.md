AutoUp-BTN
=========

This script will take an input video file, save its mediainfo, create a torrent file and upload it to BTN.

THIS SCRIPT IS NOT FINISHED AND IS EXTREMELY EXPERIMENTAL.

## Requirements

* Python2
* Python Mechanize (http://wwwsearch.sourceforge.net/mechanize/)
* Mktorrent (http://mktorrent.sourceforge.net/)
* Cfscrape (easy_install cfscrape)

## Instructions

1. Edit btn.py and fill in the required fields.
2. Run it - `python btn.py TV.Show.S01E01.720p.HDTV.x264-BTN.mkv TV.Show2.S01E01.720p.HDTV.x264-BTN.mkv ... TV.ShowN.S01E01.720p.HDTV.x264-BTN.mkv`

## To Do

* Unrar support
* Better error checking
* Support for series uploads
