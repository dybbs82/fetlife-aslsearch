# FetLife Age/Sex/Location Search

The FetLife Age/Sex/Location Search user script allows you to search for profiles on [FetLife](https://fetlife.com/) by age, sex, location, or orientation. This user script implements what is, as of this writing, the [most popular suggestion in the FetLife suggestion box](https://fetlife.com/improvements/78):

> Search for people by Location/Sex/Orientation/Age
>
> Increase the detail of the kinkster search by allowing us to narrow the definition of the search by the traditional fields.

With the FetLife Age/Sex/Location Search user script installed, a few clicks will save hours of time. Now you can find profiles that match your specified criteria in a matter of seconds. The script even lets you send a message to the profiles you found right from the search results list.

## System requirements

The following software must be installed on your system before installing the FetLife Age/Sex/Location Search user script.

### Mozilla Firefox

If you use the [Mozilla Firefox](http://getfirefox.com/) web browser (version 12.0 or higher), ensure you have the [Greasemonkey extension](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) installed (at version 1.0 or higher).

### Google Chrome

If you use the [Google Chrome](https://chrome.google.com/) web browser (version 23 or higher), ensure you have the [Tampermonkey extension](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) installed.

## Installing

To install FetLife Age/Sex/Location Search, go to [http://maybemaimed.com/playground/fetlife-aslsearch/](http://maybemaimed.com/playground/fetlife-aslsearch/) and click the "[Download and install](https://github.com/meitar/fetlife-aslsearch/raw/master/fetlife-age-sex-location-search.user.js)" near the middle of the page:

> [Download and install FetLife Age/Sex/Location Search](https://github.com/meitar/fetlife-aslsearch/raw/master/fetlife-age-sex-location-search.user.js)

If you enjoy this script, please consider tossing a few metaphorical coins in [my cyberbusking hat](http://maybemaimed.com/cyberbusking/). :) Your donations are sincerely appreciated! Can't afford to part with any coin? It's cool. [Tweet your appreciation, instead](https://twitter.com/intent/tweet?text=Ever%20wanted%20to%20search%20%23FetLife%20profiles%20by%20age%2Fsex%2Flocation%2Frole%3F%20Now%20we%20can%3A%20http%3A%2F%2Fmaybemaimed.com%2Fplayground%2Ffetlife-aslsearch%2F%20All%20thx%20to%20%40maymaym%3A%20http%3A%2F%2Fmaybemaimed.com%2Fcyberbusking%2F).

If [maybemaimed.com is censored](http://maybemaimed.com/where-im-censored/) where you are, you can alternatively go to [the Userscripts.org page for FetLife Age/Sex/Location Search](https://userscripts.org/scripts/show/146293) and click on "[Install](http://userscripts.org/scripts/source/146293.user.js)". If the script is also unavailable at Userscripts.org, you can download and install it directly from [GitHub.com](https://github.com/meitar/fetlife-aslsearch/raw/master/fetlife-age-sex-location-search.user.js).

## Using

To use FetLife Age/Sex/Location Search, [log in to your FetLife.com account](https://fetlife.com/login) and click the "A/S/L?" checkbox in the top navigation bar, near the Search box.

You will be presented with a number of additional options that allow you to define your search criteria based on profile fields. Enter your desired search criteria, as shown.

![Screenshot of form fields for FetLife Age/Sex/Location Search.](http://i.imgur.com/k6YEm.png)

The image above shows selections that will search for the profile of any person whose gender/sex is Male or FtM, who is between the ages of 21 and 28 (inclusive), and who identifies as a submissive, slave, pet,  bottom, or masochist. Once you've made your selections, click the `Mine! (I mean, uh, search…)` button. A progress bar will replace the search button showing you how many pages have been searched for a match, as shown below:

![Screenshot of FetLife Age/Sex/Location Search running a search.](http://i.imgur.com/zRBnN.png)

When a match is found, it will automatically appear with a link allowing you to send a message to them. The progress bar will again be replaced with a button allowing you to continue the search. This is shown in the image below:

![Screenshot of FetLife Age/Sex/Location Search having found a match.](http://i.imgur.com/0p66t.png)

When you're viewing any group, event, fetish, Kinkster Search result, or user profile page, you'll also be given the option to filter your search to members of the group, attendees of the event, profiles with that fetish, profiles that match the search result set, or user's friend list regardless of the geographic location listed in their profile. You can optionally filter these group, event, fetish, Kinkster Search result, or user's friend list search results by entering the name of a city, state, or country. Leave the `located in` field blank if you don't want to filter the results.

To start a new search, simply reload the page.

## Frequently Asked Questions

Before you report a new issue with FetLife Age/Sex/Location Search, please check to ensure your question is not already addressed in the list below.

* [Can I search in a location other than my own city, state, or country?](#can-i-search-in-a-location-other-than-my-own-city-state-or-country)
* [Why can I only search for men, not women?](#why-can-i-only-search-for-men-not-women)

### Can I search in a location other than my own city, state, or country?

The current version of FetLife Age/Sex/Location Search doesn't provide an interface for you to choose a location directly. However, you can temporarily change the location you list on your own profile to search in different regions. In other words, if you're currently in New York City but want to search for people in Tokyo, temporarily change your FetLife profile's location to Tokyo and run your search again. Afterwards, you can change your FetLife profile's location back to New York City.

As of version 0.3.6 of the FetLife Age/Sex/Location Search script, you can also view any group, event, fetish, Kinkster Search result, or user profile page to search for users in that group, event, fetish, search result list, or user's friend list regardless of where they say they live.

### Why can I only search for men, not women?

Because fuck you [that's why](http://www.notjustbitchy.com/?p=496).

## Change log

* Version 0.3.7
    * Offer a "return at least X matches per search" option for finding more matches more quickly.
* Version 0.3.6
    * Added support for searching on Kinkster Search result pages. Useful for combining FetLife's search-by-username with the more advanced search filtering options provided by this script.
* Version 0.3.5.1
    * Fix bug in Google Chrome where "send ''user'' a message" returned `null`.
* Version 0.3.5:
    * Added support for searching profiles while browsing fetish lists.
* Version 0.3.4:
    * Added support for Google Chrome with the Tampermonkey extension installed.
* Version 0.3.3:
    * Added support for arbitrary location filtering by substring.
* Version 0.3.2:
    * Added support for searching user's friend list.
* Version 0.3.1:
    * Added support for event attendee searches.
* Version 0.3:
    * Added support for group membership searches.
* Version 0.2:
    * Added support for State/Province and Country searches.
* Version 0.1:
    * Initial release.
