## This Is Telegram Music UserBot To Play Music Without Being Admin

## A FASTEST AND SMOOTHEST BASED ON TG CALLS AND PYROGRAM STRING.

## 🚀 <a name="deploy"></a>Deploy

## U CAN USE THIS BUTTON WITHOUT FORK IF ERROR " Like Salesforce Violate" Then READ DOWN ONE MESSAGE 

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/LEGENDBOYOP/Music-VC)

------------

- If Error Like Salesforce Then Fork This Repo

- Then Click On Down One Button 

- [![Deploy](https://telegra.ph/file/1ded5ead2f8cc5828897a.jpg)](https://heroku.com/deploy/)


-------------

## [REPL](https://t.me/LEGEND_STRINGSESSIONBOT)
## ☁️ <a name="self_host"></a>Self Host

```bash
$ git clone https://github.com/LEGEND-OS/Music-VC
$ cd MusicPlayer
$ cp sample.env .env
< edit .env with your own values >
$ sudo docker build . -t musicplayer
$ sudo docker run musicplayer
```

## ⚒ <a name="configs"></a>Configs

- `API_ID`: Telegram app id.
- `API_HASH`: Telegram app hash.
- `SESSION`: Pyrogram string session. You can generate from [here](https://replit.com/@AsmSafone/genStr).
- `SUDOERS`: ID of sudo users (separate multiple ids with space).
- `PREFIX`: Commad prefixes (separate multiple prefix with space). Eg: `A /`
- `LANGUAGE`: An [available](#languages) bot language (can change it anytime). Default: `en`
- `CUSTOM_QUALITY`: Custom stream quality for the userbot in vc. Default: `high`

## 📄 <a name="commands"></a>Commands

Command | Description
:--- | :---
• Aping | Check if alive or not
• Astart / Ahelp | Show the help for commands
• Amode / Aswitch | Switch the stream mode (audio/video)
• Ap / Aplay [song name or youtube link] | Play a song in vc, if already playing add to queue
• Aradio / Astream [radio url or stream link] | Play a live stream in vc, if already playing add to queue
• Apl / Aplaylist [youtube playlist link] | Play the whole youtube playlist at once
• Askip / Anext | Skip to the next song
• Am / Amute | Mute the current stream
• Aum / Aunmute | Unmute the muted stream
• Aps / Apause | Pause the current stream
• Ars / Aresume | Resume the paused stream
• Alist / Aqueue | Show the songs in the queue
• Amix / Ashuffle | Shuflle the queued playlist
• Aloop / Arepeat | Enable or disable the loop mode
• Alang / Alanguage [language code] | Set the bot language in group
• Aip / Aimport | Import queue from exported file
• Aep / Aexport | Export the queue for import in future
• Astop / Aleave | Leave from vc and clear the queue

## 🗣 <a name="languages"></a>Languages

```text
en    English
```

## 📃 <a name="license"></a>License

Music Player is licenced under the GNU Affero General Public License v3.0.
Read more [here](./LICENSE).
