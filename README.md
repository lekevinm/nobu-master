Discord bot intended for personal server use, but can be added to other servers. This is a very early alpha version of Mecha Nobu so expect only basic functionality and some bugs. 

Currently hosting Mecha Nobu on my laptop so uptime is not guaranteed, may look into a Rasberry Pi or a cloud hosting solution in the future.

Written in Python using the discord.py API (rewritten version).

Can also be cloned and run on a local machine, but will require additional libraries (r6sapi, youtube_dl) for full functionality.

Uses R6S API and TRN Fortnite Tracker for game stats, Anilist API to retrieve anime/manga links, and youtube_dl to stream YouTube audio.

Still adding and refining features, no official documentation until finished.

# Useful Commands

**YouTube playback:** !play (url or query) !volume (percentage) !skip !pause !resume !queue !stop

**Game stats:** !r6 (username) !fn (username)

**MyAnimeList:** !anime (title) !manga (title)

**Miscellaneous:** !poll (question option1 option2 etc) !timer (minutes) !help
