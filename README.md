komidabot
=========

[Wout Bittremieux's `komidabot`](https://github.com/bittremieux/komidabot), adapted for [Discord](https://discordapp.com).

Requirements: `pip3 install dateparser pdfquery requests discord.py`

Reads a Discord bot token from environment variable `KOMIDABOT_TOKEN`, and prints a lunch message to all servers it's connected to upon execution. Add a line like `40 11 * * 1-5 python3 /path/to/komidabot.py` to your `crontab`, et voilà.

![Example](example.png)
