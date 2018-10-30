---
layout: post
title: About Discord Bots

---
# About Discord Bots (using discord.py)
## Background
I started developing discord bots about a year ago. I started with simpler bots but then continued onto bigger projects, connecting them with things like databases or Web APIs. My first semi-big project was the [jcbsbot](https://github.com/jcb1317/jcbsbot) (The name sucks, I know. Also, this is an old, archived version), which was later renamed `Amadeus` after the AI Amadeus from Steins;Gate 0. Now, I didn't learn `discord.py` systematically nor was (or am) I very creative, so I first wrote my command matching using **huge, nested** If-Clauses. But on this project, I wrote a "more elegant" recognition system. Know, that was a "long time" ago. In the meantime, I have developed a shit ton of bots for servers and a lot of unfinished projects and a really bad command matching system called [OpenBot](https://github.com/jcb1317/OpenBot).
## Tips
Now here are a few tips I wish I knew when I started:
- Don't use `requests`, use `aiohttp`. Requests will freeze your entire bot for the duration of every single request.
- `KISS` applies in discord bot development as well. Keep it simple, stupid
- Distribute your project amongst files, It will improve maintainability by a huge margin

## My current project:
As of now, I am working on a personal project named `Robocob`. It is open-source and available [here](https://git.jacobjaeger.net/jacobjaeger/privcord).