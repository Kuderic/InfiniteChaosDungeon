# InfiniteChaosDungeon
Lost Ark Infinite Chaos Dungeon Bot. This is my first attempt at an MMORPG bot.

![ICD Banner](https://i.redd.it/77wiu2hy5eq81.jpg)

## How to Use
### Windows
Download the provided .exe file and run it. This file includes all dependencies, so it will work by itself. Alternatively, you can download the source code and its dependencies, and run the `main.py` script to get the same result.

## FAQ
### Q: Will I get banned?
A: No idea lol. Use at your own peril.
### Q: Can I minimize my game while this runs?
A: No. This is a pixel bot, so you need to keep the game open so that it can tell what's going on. For this reason, I recommend leaving the bot on overnight while you aren't playing. The alternative to a pixel bot would be to bypass EasyAntiChat and use packet sniffing and injection, but this is *substantially* harder to code and test. I might try this later with a VPN and throwaway account, though.

## Development

### Bypassing EasyAntiCheat (EAC)
EAC is the anti-cheat software developped by Epic Games, and this is used in Lost Ark. This software makes botting a pain in the behind because you cannot inject, attach a debugger, or do anything else to the game until you [bypass EAC](https://guidedhacking.com/threads/how-to-bypass-eac-easy-anti-cheat.15956/).

### Avoiding bot detection and getting banned
To avoid bot detection, I pass all inputs through a wrapper function to randomize keystroke delay in order to mimick human input. The bot also doesn't follow the same pattern every time, and it rests periodically, just like a (non-degenerate) gamer would.

## External Resources for Learning to Bot:
I referenced these while developing:
* [Injecting, packet sniffing, and reverse engineering to make an MMO bot](https://guidedhacking.com/threads/how-to-make-an-mmo-bot-mmorpg-bot-automation.15173/)
* [Bypassing EAC](https://guidedhacking.com/threads/how-to-bypass-eac-easy-anti-cheat.15956/)
