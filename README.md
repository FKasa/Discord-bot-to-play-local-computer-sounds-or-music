# Based on DLMP3 Bot (Discord.JS Local MP3)
Link to original: https://github.com/Alee14/DLMP3

A Discord bot that plays local audio files. Written in Discord.JS.

# Configuration
Make a new file called `config.json`.
```
{
    "token": "token_here",
    "prefix": "dl:",
    "botOwner": "your_user_id_here",
    "statusChannel": "channel_id",
    "voiceChannel": "voice_channel_id"
}
```

Add your own audio files to the `music` folder.

Launch the bot using `node bot.js` in terminal.

# Help Command
```
Public Only
-----------
help - Displays commands.
ping - Pong!
git - Links to the source repo.
playing - Tells you what it's playing at the moment.
about - About the bot.

Bot Owner Only
--------------
join - Joins voice chat.
resume - Resumes music.
pause - Pauses music.
skip - Skips the audio track.
leave - Leaves voice chat.
stop - Stops bot.
```
