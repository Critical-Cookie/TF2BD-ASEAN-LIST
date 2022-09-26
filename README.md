# TF2BD-ASEAN-LIST
List and Rules for TF2BD (TF2 Bot Detector by pazerOP). Designed for 
ASEAN region bots not found in the other lists or rules such as the 
Enigmaballz Bots.
- (Check out our Discord! at https://discord.gg/QqR7d6vRqX)

- (If you feel you've been false marked in any of my lists or rules, please email me at criticalcookie@whowho.anonaddy.me)

__Bots included in this list originate from the following country's gameservers__

- [x] Singapore
- [x] Hong Kong
- [x] India

Legend: 
- [ ] = Not yet supported
- [x] = supported

###### Please keep in mind this is a HOBBY Project of mine, and as such, updates/responses to issues can either be constant or not til I return a century later :P.
###### If the issue is absolutely urgent (Rules false flagging innocents, or a false positive is incorrectly added to the list) I will reply, however please be patient, I am still a freshman after all.

**_PazerOP's TF2 Bot Detector can be found at https://github.com/PazerOP/tf2_bot_detector_**


## What are the use cases of either list or ruleset?

- The WIP rules.asean.json is made for ONLY BOTS detection
so I can keep what's left of my Insanity rather than go through another hundred hashes of UUID's when manually adding new bots to the playerlist.

- The playerlist.asean.json is made for _BOTH_ Bots _AND_ Bot Hosters/Cheaters within ASEAN Casual servers that are not found within the TF2 BD's official list. 
please note this will also contain some of my suspicious markings for players who i've deemed suspicious.
Those deemed suspicious must hit multiple suspicious factors, such as a VAC ban younger than 2 years and suspicious gameplay that's beyond professional.

I recommend using BOTH at the same time for efficient Bot detection in South East Asian servers! As well as disabling TF2 BD's Chat messages for efficiently stealth marking all Bots!
(Tell people about the bots the old fashioned away, via text chat)
 

## Can I contribute?

At the moment I will be the only Author, as this pet project of mine is extremely new.
This is also done for authenticity and trust reasons. 

This way you will have only me and my hatred for bots to have given your trust.

I will be allowing public contributions in the future for me and a set of trusted authors to filter through,
but as of now, I'd like this project and contributions to be maintained by just me.


* Note: Contributions can be suggested within our Discord group



## Ok cool, how do I use this then?

You can download the entire contents as a zip file via clicking the CODE dropdown.
Save any of the individual json files that you want to use 
within your TF2 Bot Detectors cfg folder, and don't change the file names.
Start up TF2 BD and the tool will take care of the rest.
(I recommend using Direct Steam API Integration for the best performance using TF2BD as described in this TF2BD Wiki Entry = https://github.com/PazerOP/tf2_bot_detector/wiki/Integrations:-Steam-API)

## Hey, your Steam Name rules are broken in ruleset.asean.json!

As of now, 26th August 2021, only the latest Nightly build of TF2 Bot Detector supports Steam Name detection via Moebs excellent contribution, the current stable build cannot understand what "personaname_message_text" means, therefore it will discard it and leave the rule entry as null.

I have taken such problems into consideration, and will write my rules with this handicap in mind to ensure that the Username only rules will be as efficient as possible in catching new unrecorded Bots!


## I like your work, but I don't trust you'll keep it to just Bots and Bot Hosters only. What if you're a troll and start adding legit players? Or get hacked?

While either of those assumptions are next to impossible, 

I made this project for the purpose of an easier time dealing with Bots that the default Bot Detectors lists have trouble marking.

I absolutely would do my best to upkeep a decent level of trust with you, whether I know you personally, as a steam friend, or even as a stranger.

However, if you feel worried about the above statement, the live update feature can be removed in either projects, simply open them within a text editor

and remove the entire line that starts with...

"update_url"

_Note: (please don't just remove the URL, as update_url will attempt to look for a URL that's not there, not find it, and will not accept the list/ruleset into the tool)_

## Hey I found "x" Bots called "name" that isn't on your list, but found in Asian TF2 servers!

I'll look into these if they are common enough to be included into my list, but if these bots can already be found in either the TF2 BD's Official/Trusted Rulesets/Lists then I won't
include them in mine.

The purpose of my pet project is to include Asian Bots that are NOT within any of the official TF2 BD lists, for better Quality Of Life for asian TF2 BD users.
(Bots only found within Trusted may have an exception, since many TF2 BD users may only be using Official, and not Trusted, since Trusted must be manually downloaded)


## I found UUID's or Rules that are targetting legitimate players/falsely targetting me!
Please send in details of the false positive in the Discord server above within the issue channel, or send me a personal email in the email address above as well, and we can discuss a compromise/verify the false flag.

