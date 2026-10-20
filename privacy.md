---
title: Sankha Privacy Policy
---

# Privacy Policy

_Effective date: 20 October 2026_

Sankha ("the bot") is a Discord bot that plays a short entrance song when a member joins a voice channel.
This policy explains what data Sankha stores, why, and how you can have it deleted.

## What Sankha stores

Sankha stores only what it needs to play entrance songs:

- **Discord IDs:** the ID of each server that uses Sankha and the user ID of each member who has an entrance song,
  or who is an entry admin in a server.
- **Entrance settings:** for each member's entrance in a server: the clip's start time, length and volume, and the
  song's source: the YouTube link and video title, or the name of the uploaded audio file.
- **Audio files:** the audio of each entrance song, downloaded from the YouTube link a member provided or uploaded
  by a server owner or entry admin.
- **Entry admin list:** which members a server owner has made entry admins in that server.
- **Server logs:** technical logs of what the bot does (for example "entrance played for user ID X in channel Y"),
  including Discord user IDs, voice channel names and YouTube links. Logs are used only to fix problems and are
  deleted after 30 days.

Sankha does **not** read or store messages, does not track your activity or presence, does not collect your email,
IP address or payment details, and does not use your data for advertising or analytics.

Sankha keeps a short-lived, in-memory record of when your entrance last played (to apply a 10-second replay
cooldown). It is never written to disk and is cleared whenever the bot restarts.

## How the data is used

Only to provide the bot's features: playing your entrance song when you join voice, and showing entrance settings
with `/myentry` and `/entries`. Data from one server is never shown in another server.

## Who can see it

- Members of a server can see that server's entrance list (`/entries`): each member's song title or file name and
  their start, length and volume settings.
- The bot's developer can access the stored data and logs on the server that runs Sankha, only to operate and
  fix the bot.
- Sankha does not sell, rent or share your data with anyone.

## Services Sankha relies on

- **Discord**, to receive commands and voice events and to play audio. See Discord's Privacy Policy.
- **Oracle Cloud** (data center in Mumbai, India), which hosts the bot and stores the data above.
- **YouTube**, from which the bot downloads the audio for links members provide. YouTube sees a request for that
  video from the bot's server; it does not receive your Discord identity.

## How long data is kept

- Entrance settings and audio files: until the member removes their entrance (`/removeentry`), a server owner or
  entry admin removes it, or Sankha is removed from that server, which deletes that server's data.
- Entry admin list: until the server owner removes the admin or Sankha is removed from the server.
- Server logs: 30 days.
- Backups: a nightly copy of the stored data and audio files is kept for 30 days (on the bot's server and on the
  developer's computer) so it can be restored after a failure, then deleted. Anything you delete disappears from
  the backups within 30 days.

## Your choices and deletion

- Remove your own entrance song and its audio file at any time with `/removeentry`.
- Server owners can remove all of Sankha's data for their server by removing Sankha from the server.
- To ask for deletion of all your data across every server, or for a copy of it, contact us (below).
  Requests are handled within 30 days.

## Children

Sankha is meant for people who meet Discord's minimum age in their country. It does not knowingly collect data
from anyone below that age.

## Changes

If this policy changes, the new version will be posted at this link with a new effective date.

## Contact

Email **[sankha.bot@gmail.com](mailto:sankha.bot@gmail.com)**. Please include your Discord user ID and the server's name or ID so the request can be found.
