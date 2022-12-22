# Awesome Mastodon [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

[<img src="https://rawgit.com/tleb/awesome-mastodon/master/mastodon-logo.svg" align="right" width="150">](https://joinmastodon.org)

> Up-to-date and curated list of Mastodon-related stuff!

Forked from [tleb/awesome-mastodon](https://github.com/tleb/awesome-mastodon/edit/master/README.md) because that was no longer being updated.

**Mastodon is the world's largest free, open-source, decentralized microblogging network**. See the [Official](#official) category to learn more about the network.

## Contents

* [Official](#official)
* [Clients](#clients)
* [Federated servers](#federated-servers)
* [Tools](#tools)
* [User styles](#user-styles)
* [User scripts](#user-scripts)
* [Bots](#bots)
* [News & magazines bots](#news--magazines-bots)
* [Associations](#associatons)
* [Blogs](#blogs)
* [Libraries](#libraries)
* [Hosting](#hosting)
* [Browser Extensions](#extensions)

## Official

* [Website](https://joinmastodon.org)
* [GitHub repository](https://github.com/tootsuite/mastodon)
* [Documentation & official explaination](https://docs.joinmastodon.org/)
* [API documentation](https://docs.joinmastodon.org/client/intro/)

## Clients

### Web

* [Tooty](https://github.com/n1k0/tooty) - Experimental multi-account Mastodon Web client (Elm).
* [naumanni](https://github.com/naumanni/naumanni) - Web user interface specially designed for Mastodon.
* [Pinafore](https://github.com/nolanlawson/pinafore) - Alternative web client for Mastodon, focused on speed and simplicity.
* [Brutaldon](https://git.carcosa.net/jmcbray/brutaldon) - Brutaldon is a brutalist, Web 1.0 web interface for Mastodon.
* [Halcyon](https://notabug.org/halcyon-suite/halcyon) - Alternative web client for Mastodon and Pleroma with a Twitter-like interface.
* [Planiverse](https://git.mulligrubs.me/planiverse/) - Minimalist, no-JS Web client for Mastodon.
* [Sengi](https://nicolasconstant.github.io/sengi/) - Desktop oriented webapp for Mastodon and Pleroma, focused on multi-accounts usages.
* [Phanpy](https://github.com/cheeaun/phanpy) - a minimalistic, opinionated web client for Mastodon

### Mobile

* [Mastodon](https://joinmastodon.org/apps) - official Mastodon mobile app, available for both [Android](https://play.google.com/store/apps/details?id=org.joinmastodon.android) and [iOS](https://apps.apple.com/us/app/mastodon-for-iphone/id1571998974)
* [tooot](https://tooot.app/) - simple, elegant, open source mobile client, available for both [Android](https://play.google.com/store/apps/details?id=com.xmflsct.app.tooot) and [iOS](https://apps.apple.com/app/id1549772269)


#### Android

* [Tusky](https://play.google.com/store/apps/details?id=com.keylesspalace.tusky) - Android client.
* [Twidere](https://f-droid.org/packages/org.mariotaku.twidere/) - Android app for Twitter, GNU Social and Mastodon.
* [Fedilab](https://framagit.org/tom79/fedilab) - Android client.
* [Subway Tooter](https://github.com/tateisu/SubwayTooter) - highly customisable Mastodon client for Android made by a Japanese developer
* [Husky](https://husky.adol.pw/) - Pleroma and Mastodon client for Android

#### iOS

* [Toot!](https://apps.apple.com/us/app/toot/id1229021451) - paid Mastodon client for iOS.
* [Metatext](https://metabolist.org/) - open source client for iOS; development has currently been suspended
* [Mercury for Mastodon](https://apps.apple.com/us/app/mercury-for-mastodon/id1486749200) - free Mastodon client for iOS
* [Mastoot](https://apps.apple.com/us/app/mastoot/id1501485410) - simple, free Mastodon client for iOS
* [Mast: for Mastodon](https://apps.apple.com/us/app/mast-for-mastodon/id1437429129) - paid Mastodon client for iOS
* [Mammoth](https://testflight.apple.com/join/HyL7boSn) - Mastodon client for iOS by the maker of Aviary for Twitter, still in beta
* [Ivory](https://tapbots.social/@ivory) - Mastodon client for iOS by Tapbots, still in alpha

#### SailfishOS

* [Tooter](https://github.com/dysk0/harbour-tooter) - Native client for SailfishOS.

### Desktop

* [Whalebird](https://whalebird.social/en/desktop/contents) - Electron-based cross-platform Mastodon client
* [Sengi](https://nicolasconstant.github.io/sengi/) - open source cross-platform Mastodon client

#### macOS

* [Mastonaut](https://apps.apple.com/us/app/mastonaut/id1450757574) - free macOS Mastodon client
* [Mast: for Mastodon](https://apps.apple.com/us/app/mast-for-mastodon/id1437429129) - paid macOS Mastodon client

#### Linux

* [Tootle](https://github.com/bleakgrey/tootle) - Simple Mastodon client designed for elementary OS.
* [Tokodon](https://apps.kde.org/en-gb/tokodon/) - open source KDE Plasma client

### CLI

* [toot](https://github.com/ihabunek/toot) - Mastodon CLI client (Python).
* [madonctl](https://github.com/McKael/madonctl) - Mastodon CLI client (Go).


## Federated services

### Microblogging

* [Mastodon](https://joinmastodon.org/) - Most popular microblogging platform.
  * [Mastodon Glitch Edition (glitch-soc)](https://glitch-soc.github.io/docs/) - a Mastodon fork with additional features such as rich text formatting and local-only toots
  * [Hometown](https://github.com/hometown-fork/hometown) - a lightweight fork of Mastodon that supports local-only toots and more content types
* [GnuSocial](https://gnu.io/social/) - Oldest microblogging platform.
* [Pleroma](https://pleroma.social/) - Lightweight, customisable microblogging platform.
  * [Akkoma](https://akkoma.social/) - a Pleroma fork with more features and a faster pace of development
* [Microblog.pub](https://microblog.pub/) - Single-user lightweight microblogging platform.
* [NextCloud Social](https://apps.nextcloud.com/apps/social) - Microblogging app for the Nextcloud platform.
* [WordPress ActivityPub](https://wordpress.org/plugins/activitypub/) - WordPress plugin for adding ActivityPub support to any WordPress site
* [GotoSocial](https://github.com/superseriousbusiness/gotosocial) - fast and efficient ActivityPub server written in Golang, still in alpha

### Blogging


* [Plume](https://joinplu.me/) - Blogging platform.
* [WriteFreely](https://writefreely.org/) - Blogging platform.

### Link aggregation

* [Prismo](https://gitlab.com/prismosuite/prismo) - Link aggregation platform.
* [Lemmy](https://join-lemmy.org/) - Reddit-like link aggregator and forum

### Others

* [Friendica](https://friendi.ca/) - Facebook/Myspace-like social network platform.
* [PixelFed](https://pixelfed.org/) - Instagram-like photograph sharing platform.
* [Peertube](https://joinpeertube.org/) - Youtube-like video sharing platform.
* [FunkWhale](https://funkwhale.audio/) - Soundcloud-like audio sharing platform.
* [Hubzilla](https://zotlabs.org/page/hubzilla/hubzilla-project) - Blog/social networks platform with file, contacts and events sharing.
* [BookWyrm](https://joinbookwyrm.com/) - Goodreads/Librarything-like book social network.

## Tools

* [Mastodon instances](https://instances.social/list) - List of Mastodon instances.
* [unmung.com/mastoview](http://www.unmung.com/mastoview) - Preview the local or federated timeline of any instance.
* [Toot scheduler](https://scheduler.mastodon.tools/) - Schedule now, toot later.
* [Last](https://framagit.org/luc/last) - Aggregate toots on a web page providing Atom feed and an epub (Perl).
* [Forget](https://forget.codl.fr/about/) - Delete toots after a user defined period of time (Python [source code](https://github.com/codl/forget/)).
* [Mastodon Toot Bookmarklet](https://rknightuk.github.io/mastodon-toot-bookmarklet/) - Bookmarklet to toot the current page ([source code](https://github.com/rknightuk/mastodon-toot-bookmarklet/))
* [Mastodon – Simplified Federation!](https://addons.mozilla.org/firefox/addon/mastodon-simplified-federation/) - Redirect clicks on remote follow/interaction buttons to your own instance ([source code](https://github.com/rugk/mastodon-simplified-federation)).
* [Fediverse Explorer](https://fediverse.0qz.fun/) - Trending hashtags and popular toots, regenerated every hour.
* [Mastodon #nowplaying Toot Bookmarklet](https://nowplaying.resynth1943.net) - Bookmarklet to toot the music you're currently listening to. Works with YouTube. ([source code](https://github.com/resynth1943/mastodon-nowplaying-toot-bookmarklet))

## User styles

* [Variable width](https://userstyles.org/styles/139721/mastodon-glitch-soc-variable-width) - Makes Mastodon scale with the browser's width.
* [Narrow drawer](https://userstyles.org/styles/141457/mastodon-dynamic-wide-columns-narrow-drawer) - With the variable width style, makes the drawer narrower and the other columns scale accordingly.

## User scripts

* [NSFW Remover](https://greasyfork.org/fr/scripts/29228-mastodon-nsfw-remover) - Automatically display NSFW images.
* [Customizable interface](https://openuserjs.org/scripts/bl00m/Mastodon_Customizable_Interface) - Move and resize columns on a grid.
* [BirdSite](https://gitlab.com/pmorinerie/birdsite) - Browser extension for cross-posting Mastodon toots to Twitter.

## Bots

* [feed2toot](https://gitlab.com/chaica/feed2toot) - Automatically parses RSS feeds, identifies new posts and posts them on Mastodon (Python).
* [usercount](https://github.com/josefkenny/usercount) - Bot which posts user statistics to Mastodon (Python).
* [autofollow](https://github.com/gled-rs/mastodon-autofollow) - Autofollow bot for Mastodon (Python).
* [hnbot](https://github.com/raymestalez/mastodon-hnbot) - Posts the Hacker News stories with 100+ points (Python).
* [translator](https://christopher.su/projects/translator/) - Translate any toot into the desired language using `@translator@toot.works [langcode]`.
* [@TrendingBot@mastodon.social](https://mastodon.social/@TrendingBot) - Shows you what's trending on Mastodon.
* [Remindr](https://gitlab.com/chaica/remindr) - Automatically send reminders to both Mastodon and Twitter from a list of resources (Python).
* [News Bot](https://botsin.space/@newsbot) - mirrors Twitter accounts on Mastodon (ClojureScript), source available on [GitHub](https://github.com/yogthos/mastodon-bot).
* [Welcome Bot](https://github.com/indyhall/mastodon-welcome-bot) - Automatically send a welcome DM to new users (Python).

## Blogs

### English

### Français

* [@HygieneMentale@oc.todon.fr](https://oc.todon.fr/@HygieneMentale) - Hygiène Mentale.
* [@journalduhacker@framapiaf.org](https://framapiaf.org/@journalduhacker) - Journal du Hacker.
* [@korbenbot@mastodon.xyz](https://mastodon.xyz/@korbenbot) - Korben (bot).

## Libraries

* [Mastodon.py](https://github.com/halcy/Mastodon.py) - Python wrapper for the Mastodon API.
* [Megalodon](https://github.com/h3poteto/megalodon) - Mastodon API client library for node.js.

## Hosting

* [Masto.host](https://masto.host) - Fully managed Mastodon hosting.

## Extensions

* [Mastodon Link](https://github.com/masrly/mastodon-link) - Adds a clickable mastodon icon next to mastodon usernames to visit their profile on your instance for ease of following
* [Mastodon View Profile](https://github.com/bramus/mastodon-view-profile) - Adds a button to the toolbar to visit a profile on your instance ease of following
