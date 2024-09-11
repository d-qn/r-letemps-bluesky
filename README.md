# R Le Temps rss Bot 


This is a fork of the bot R bloggers RSS bot <https://bsky.app/profile/r-bloggers.bsky.social>.
It parses the RSS feed of new blogs posts from the blog aggregator site https://www.r-bloggers.com/ and advertises them once per hour on Bluesky.

Learn more about the bot in [this post](https://www.johannesbgruber.eu/post/2024-01-18-building-r-bloggers-bluesky-bot-with-atrrr/) by [Johannes Gruber](https://github.com/JBGruber) 

This bot is also meant as a showcase for how to build bots on top of the [{atrrr}](https://jbgruber.github.io/atrrr/) package.
The relevant file are:

- [bot.r](bot.r): R script that collects the RSS entries and posts them
- [bot.yml](.github/workflows/bot.yml) the Github action script running the bot once per hour
