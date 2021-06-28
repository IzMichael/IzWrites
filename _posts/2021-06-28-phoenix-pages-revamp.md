---
tag: The-Phoenix-Pages
category: DevLogs
title: The Great Revamp!
---
So, after a month and a half of working on this, I am proud to announce V2 of The Phoenix Pages!

### What's new in V2
- Retired the Web UI
- Migrated the database to a cloud-hosted API
- Introduced Locations
- Added `p!loc` command to the Discord Bot
- Added `p!submit` command to the Discord Bot
- Added `p!update` command to the Discord Bot

### So, what's actually changed?
##### Retired the Web UI
With the recent introduction of the Discord Bot, I've decided to retire the [Web UI](https://phoenix-pages.izmichael.xyz/). It was the original form of The Phoenix Pages, and I'll miss it. I may bring it back at some point, but I just don't have the time to continuously maintain it. All of its features have migrated to the Discord Bot.

##### Migrated the database to a cloud-hosted API
The full Phoenix Pages database is now stored on the cloud, which makes adding, editing, and reading the database so much easier.

##### Introduced Locations
Locations! You can now easily find where in the world a shop is! Along with the standard XYZ coordinates, you can now find the City, District, or Base that the shop is in.
![Screenshot of the new Locations](/assets/images/pages-new-locations.png)

As part of the new Locations, you can run `p!loc <location>` to get more info about the specified Location.
![Screenshot of p!loc](/assets/images/pages-location-command.png)

##### Submit and Update Commands
`p!submit` will send you a DM with the all new submission process!
![Screenshot of p!submit](/assets/images/pages-submit-command.png)

`p!update` will send you a DM with the instructions to update your shop's info.
![Screenshot of p!update](/assets/images/pages-update-command.png)

### And that's it!
That's all the features for V2. If you've got any bug reports or feature suggestions, please DM the bot (@The Phoenix Pages#2209). Happy Shopping!