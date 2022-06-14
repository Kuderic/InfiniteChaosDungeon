# InfiniteChaosDungeon
### Lost Ark Infinite Chaos Dungeon Bot.

![ICD Banner](https://i.redd.it/77wiu2hy5eq81.jpg)

## How to Use
### Windows
Download the provided `InfiniteChaosDungeon.exe` file and run it. Alternatively, you can download the source code, run `pipenv install` to download and install the appropriate dependencies, and then run `main.py` to launch the program.

## FAQ
### Q: Will I get banned?
A: No idea lol. Use at your own peril.
### Q: Can I minimize my game while this runs?
A: No. This is a **pixel bot**, so you need to keep the game open so that it can tell what's going on. For this reason, I recommend leaving the bot on overnight while you aren't playing. The alternative to a pixel bot would be to bypass **EasyAntiCheat** and use packet sniffing and injection, but this is *substantially* harder to code and test. I might try this later with a VPN and throwaway account, though.
### Q: What is EasyAntiCheat (EAC)?
A: EAC is the anti-cheat software developed by Epic Games and used by Lost Ark. This software makes botting a pain in the behind because you cannot inject, attach a debugger, or do anything else to the game unless you [bypass EAC](https://guidedhacking.com/threads/how-to-bypass-eac-easy-anti-cheat.15956/). This bot does not bypass EAC and instead sends input through your game screen.

## Development

### Avoiding Bot Detection and Bans
To avoid bot detection, I pass all inputs through a wrapper function to randomize keystroke delay in order to mimick human input. The bot also doesn't follow the same pattern every time, and it rests periodically, just like a (non-degenerate) gamer would.

## External Resources for Learning to Make A Bot:
I referenced these while developing:
* [Injecting, packet sniffing, and reverse engineering to make an MMO bot](https://guidedhacking.com/threads/how-to-make-an-mmo-bot-mmorpg-bot-automation.15173/)
* [Bypassing EAC](https://guidedhacking.com/threads/how-to-bypass-eac-easy-anti-cheat.15956/)

## Inspiration:
https://www.elitepvpers.com/forum/lost-ark-trading/5014211-lost-ark-megabot-100-undetected-chaos-farming-fishing-calculator-all-one.html
