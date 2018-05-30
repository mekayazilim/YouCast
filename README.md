YouCast
=======

[![All Releases](https://img.shields.io/github/downloads/i3arnon/YouCast/total.svg)](https://github.com/i3arnon/YouCast/releases)
[![Release](https://img.shields.io/github/release/i3arnon/YouCast.svg)](https://github.com/i3arnon/YouCast/releases)
[![License](https://img.shields.io/github/license/i3arnon/YouCast.svg)](LICENSE)

YouCast allows you to subscribe to channels and playlists on YouTube as video and audio podcasts in any standard podcast app (e.g. Overcast, iTunes, BeyondPod, etc.).

<p align="center"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://raw.githubusercontent.com/I3arnon/YouCast/master/src/Screenshot.PNG" alt="Screenshot" width="463" height="295" /></p>

<p align="center"><a href="http://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=B8VLNS5S6UBEE"><img style="display: block; margin-left: auto; margin-right: auto;" src="http://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG_global.gif" alt="" /></a></p>

## Features
 - Subscribe to any channel's public video uploads.
 - Subscribe to any public playlist on YouTube.
 - Get audio-only feeds (for faster downloads).
 - Sort the videos by popularity (awesome for huge channels, like TED Talks)
 - Run YouCast at home and access it from everywhere on the internet, not just your home network.
 - Limit the amount of videos in any feed (helps with users with thousands of videos).
 - Use YouCast from any device in your network: iPhone, Android, Tablet. (Just open the incoming port 22703 on your firewall and paste the URL in your podcast app)

## Usage
To get a URL for a podcast:

1. Open YouCast
1. Enter a YouTube channel's username or playlist ID.
1. Choose audio or video quality (the better the quality the bigger the file).
1. Generate and copy the podcast URL.
1. Paste the URL in your favorite podcast app.
1. While your app is updating podcasts YouCast must be running.

## Known Issues

1. Explicit/restricted videos can't be downloaded (they require YouCast to login with a user)
1. Audio feed episodes on iOS are 2X in length (second half is silent)
