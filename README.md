# Advanced BBCode Box 3.1

Replace phpBB3's BBCode buttons with icons in an attractive and customizable toolbar. This extension also adds many new and useful custom BBCodes giving users more ways to customize their posts, including BBvideo (embed videos from dozens of media sites). Custom BBCodes can be arranged and sorted in any order and assigned to specific usergroups (such as Moderators and Admins only).

[![Build Status](https://travis-ci.org/VSEphpbb/abbc3.png)](https://travis-ci.org/VSEphpbb/abbc3)
[![Dev dependencies](https://david-dm.org/VSEphpbb/abbc3.png)](https://david-dm.org/VSEphpbb/abbc3#info=devDependencies)

## Features:
* Customizable icon-based BBCode toolbar
* Custom BBCode sorting/arrangement
* BBCodes can be assigned to certain usergroups for private use.
* Supports phpBB3’s custom BBCodes.
* New BBCodes:

		Copy, Paste, Plain, Font Family, Highlight text, Strike through text,
		Superscript, Subscript, Glow text, Shadow text, Dropshadow text, Blur
		text, Fade In/Out, Align (Left, Right Center, Justify), Float (Left,
		Right), LTR/RTL Direction, Preformatted text, Marquee scroll, Spoiler,
		Hidden, Moderator Message, Off Topic, NFO/ascii text, YouTube, BBvideo

* Embed video in your posts with BBvideo, supported video sharing sites:

		5min.com, allocine.fr, on.aol.com, blip.tv, break.com, clipfish.de,
		clipmoon.com, cnbc.com, cnettv.cnet.com, colbertnation.com,
		collegehumor.com, comedycentral.com, crackle.com, dailymotion.com,
		dotsub.com, ebaumsworld.com, facebook.com, flickr.com, funnyordie.com,
		g4tv.com, gameprotv.com, gamespot.com, gametrailers.com, godtube.com,
		howcast.com, hulu.com, ign.com, instagram.com, liveleak.com,
		metacafe.com, moddb.com, mpora.com, msnbc.msn.com, myspace.com,
		myvideo.de, photobucket.com, revision3.com, rutube.ru, sapo.pt,
		screen.yahoo.com, screenr.com, scribd.com, sevenload.com,
		slideshare.net, snotr.com, soundcloud.com, spike.com, streetfire.net,
		ted.com, testtube.com, thedailyshow.cc.com, theonion.com, tudou.com,
		tu.tv, twitch.tv, twitvid.com, ustream.tv, vbox7.com, veoh.com,
		vevo.com, viddler.com, videogamer.com, videu.de, vimeo.com, vine.co,
		wat.tv, youku.com, youtu.be, youtube.com

### Languages supported:
* English
* French
* German
* Hebrew
* Persian
* Polish
* Spanish

## Requirements
* phpBB 3.1.0-RC2 or higher
* PHP 5.3.3 or higher
* Javascript is required by this extension.

Note: This extension is in development. Installation is only recommended for testing purposes and is not supported on live boards. This extension will be officially released following phpBB 3.1.0.

## Installation
1. [Download the latest release](https://github.com/VSEphpbb/abbc3/releases) and unzip it.
2. Copy the entire contents from the unzipped folder to `phpBB/ext/vse/abbc3/`.
3. Navigate in the ACP to `Customise -> Manage extensions`.
4. Find Advanced BBCode Box under "Disabled Extensions" and click `Enable`.

## Uninstallation
1. Navigate in the ACP to `Customise -> Manage extensions`.
2. Click the `Disable` link for Advanced BBCode Box.
3. To permanently uninstall, click `Delete Data`, then delete the `abbc3` folder from `phpBB/ext/vse/`.

## Customizing:
1. Custom BBCode Icons: You can give your custom BBCodes icons by simply adding a GIF image named after your BBCode (e.g.: center.gif) to the `images/icons` directory. There are tons of extra BBCode icons included in the `contrib` directory.
2. BBCode Toolbar: You can change the look of the BBCode toolbar using any of the extra toolbar background images located in the `contrib` directory. Just copy one of the alternative toolbar images to `styles/all/theme/images/abbc3_bg.gif` (and refresh your browser).
3. NOTE: When making any of these customizations to ABBC3, be sure to note/backup your changes, as you may need to reproduce them after updating this extension, in case any of your added image files is overwritten or erased.

* * *

## Deprecated ABBC 3.0 Information:
[ABBC 3.0](https://github.com/VSEphpbb/Advanced-BBCode-Box-3) is a popular MOD for phpBB 3.0. Due to the changes in the new Extensions system for phpBB 3.1, ABBC 3.1 has been re-built from scratch. It can not simply be ported over from 3.0 to 3.1. The following is a list of what has been removed:

* BBCode posting page assignments are no longer available (display on posting, on signature, on private message)
* BBCode toolbar user options (no more "compact mode" or "disabled mode")
* Image Resizers
* Removed BBCodes:
	- Unable to convert or maintain backwards compatability:

			Anchor, Horizontal line, Rainbow text, Indent, Click counter, Search text,
			Tables, Tabs, Thumbnail images

	- Deprecated:

			Ed2k, Imgshack, Rapidshare, Testlink, FLV, Quicktime mov, Real Player ram,
			Scrippet, Stream, Video, Web, Wave

* Removed BBvideos:
	- direct file types: `mp4, m4v, mov, dv, qt, mpg, mpeg, avi, wmv, flv, swf, mp3, mid, midi, ram`

* * *

## License
[GNU General Public License v2](http://opensource.org/licenses/GPL-2.0)

© 2013 - Matt Friedman (VSE)
