# Introduction

So, you're new to Debrid Media Manager more commonly known as DMM!

DMM, in short, is a web-based manager for organizing and maintaining your Real-Debrid or AllDebrid library.

Here are some tips and tricks to allow you to maximize your use of DMM, while also providing a step-by-step guide on how to address a variety of circumstances.

## Navigating Debrid Media Manager

Upon logging in, you will be presented with the main screen. You should familiarize yourself with this landing page, as there are a plethora of options to choose from.

## Headings should be indented

### 3rd levels always go under 2nd levels

#### 4ths go under 3rds

#### this will never show up in TOC

### But this will

## and so will this

## Bulleted lists

* Should use asterisks
  * Can be indented
  * But not always

1. Can also be numbered
2. Numbers must be sequential

!!! warning "I am a warning"
    I am an "admonition"

![Screenshot of Debrid Media Manager login page](/images/dmm-home.png)

### Common options

#### Login Options

Pick from one of the following:

* Real-Debrid
* AllDebrid
* Trakt

#### Library

Allows you to view and and maintain your Real-Debrid library. This is your own personal RD account, represented in DMM.

#### Hash Lists
Hash lists are public shares of hashes provided by DMM users.

Allows you to view and utilize available hash lists.

#### Search
Search for an item to add to your library

#### Stemio
This function allows you to cast from any device to Stremio.

#### Settings
Allows you to search the available content.

#### Anime
An anime-specific search function of available content.

#### Video player
There are a variety of options here for you to explore.
- Biggest movie size to show
- Biggest episode size to show
- Default torrents filter:
- Only show trusted torrents:
  - In general, “trusted torrents” are simply ones which include IMDb ID tags.
- Top
  - The top content in terms of activity.
- Recent
  - Recently updated content.
- Movies
- Shows

**2.) VIEWING AND MAINTAINING YOUR LIBRARY**

Once you have reached the library screen, you will be able to view all of the items inside your Real-Debrid library. Near the top of the screen, you will notice a variety of buttons which will provide you with a number of ways in which you can interact with your library.

To begin with, we will focus on the buttons labeled as "Failed" & "No seeds"

**Removing failed and no seed items**

Please be aware, these two buttons will only appear if you do in fact have either failed items or items without any seeds. Clicking on either of these buttons will display a list of items that are relevant to the label of that button. Once you are viewing either of these lists, you can select and delete these items from your library if you wish. **NOTE: Ensure that you are viewing these library categories and not your general library before deleting items.**

## Reintroducing un-cached items

Occasionally, you might find that you need to reinsert items that have been un-cached by Real-Debrid. This occurs when a file has not been accessed in 14 days. This is expected behavior and can be fixed simply by reinserting those items.

To achieve this, near the top of your library page you will use a button labeled ”Uncached" and selecting this button will show you what has recently been un-cached from Real-Debrid. ***Please note, this button will at times appear even when you do not have any such items.*** While viewing these items you can use the green button labeled "Reinsert List" and selecting this will then attempt to redownload those items back into Real-Debrid’s cache.

**Error Messages**

At times you might see an error message suggesting something along the lines of, "cannot add torrent_1738383ururiej_infringing_file". This generally indicates that Real-Debrid has been served a DMCA request, which they have complied with, and have removed the torrent in question. Therefore, it can no longer be added to Real-Debrid and you will need to find a replacement.

**Merging duplicate items without breaking symlinks**

Let’s set that stage with a scenario: ***You have enabled “Upgrades Allowed” in Radarr and/or Sonarr and you now have 10 identical copies of the same item.*** To remove these duplicates, you will want to locate the button near the top of the page labeled "Same title" and select it. Three additional buttons that are labeled “Size”, “Date”, and “Hash” will appear. Generally, “Hash” will be the only option you might ever want to use. Selecting this button will give you the option to merge the majority of those items which share the same hash and will do so **without** breaking your existing symlinks. Using either of the other two options of “Size” or “Date” **will** break your existing symlinks.

**3.) SO YOU WANT TO BE A DMM POWER USER?**

DMM’s settings are simple and easy to use, but did you know you can change what DMM returns before you search for it? Allow me to explain…

When you search for an item using DMM, that search request will return everything available for that item. Everything. 2160p, 1080p, 720p, WEBDL, and so on. However, what if you were only looking for specific criteria? That's where DMM's default torrent filter comes in!

On the homepage of DMM, when you select the settings icon a popup box appears. The 4th option is the one you would select. This is a text filter in which you can type, for example, "1080" or "4K". Now when you search for items, it will only return those which match your chosen criteria. The text filter is space separated and every term is evaluated as "and". This allows you to also combine criteria in your filter.

***To be continued…***

Credit to <@1203101145833275503> for creating the original version of this document, with valuable contributions also made by <@136543011268984833>.

If you're not using DMM's userscript <https://greasyfork.org/en/scripts/463268-debrid-media-manager> then you're not a Power User 😉  All this does is add a DMM link to different movie, tv show, anime sites so that you don't have to search in DMM.

You can see all supported sites on the code <https://greasyfork.org/en/scripts/463268-debrid-media-manager/code>

- anidb.net
- icheckmovies.com
- imdb.com
- justwatch.com
- kitsu.io
- letterboxd.com
- mdblist.com
- myanimelist.net
- themoviedb.org
- thetvdb.com
- trakt.tv

There are also web extensions available but the review process takes time for these platforms so new releases are delayed a bit:

<https://chromewebstore.google.com/detail/debrid-media-manager/fahmnboccjgkbeeianfdiohbbgmgoibb>
<https://addons.mozilla.org/en-US/firefox/addon/debrid-media-manager/>
Safari coming soon^tm
