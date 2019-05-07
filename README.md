# 10FastFingers.com Bot with AntiAntiCheat

[10fastfingers](www.10fastfingers.com) is a speed typing website where you can test your typing speed.

Me being bored and busy with other important tasks, I decide that it'd be best to ignore them and create a bot, how responsible.

## What it does

This bot will type in the words for you as fast as you want.

Now if you choose a really high speed (like 300 words per minute),
[10fastfingers](www.10fastfingers.com) will ask you to complete an [anti-cheat test](https://10fastfingers.com/anticheat/view/1/1),
where there is an image with text in it, rather than having the raw text.

The script can also deal with this, using OCR [tesseract.js](https://tesseract.projectnaptha.com/)

## How to use

There are two ways to use this script, either by:

- pasting it in the browser's console (the simpler and quicker option)

or

- installing it as a userscript.

### Method1: Pasting to the console

1. Copy the entire script from here [here](10fastfingers_bot_antianticheat.user.js) or [RAW link](/../../raw/master/10fastfingers_bot_antianticheat.user.js) (`CTRL+A`, `CTRL+C`)
2. On the [10fastfingers](www.10fastfingers.com) page,  
    open the developer console in Google Chrome `CTRL+SHIFT+J`, then navigate to the `console` tab
4. Paste (CTRL+V), then hit (ENTER)
5. Press the `HACKIT` button that was added to the page

### Method2: Downloading a UserScript client (Tampermonkey/Greasemonkey)
1. Download a UserScript browser extension like [Tampermonkey](https://www.tampermonkey.net/)
2. Then install the script by clicking the [RAW link](/../../raw/master/10fastfingers_bot_antianticheat.user.js)
3. Reload your [10fastfingers](www.10fastfingers.com) page (CTRL+R does NOT work, you must re-enter the address in the address bar)
4. Press the `HACKIT` button that was added to the page


## Notices

- This script is made purely for educational purposes
- This script uses [Tesseract.js](https://tesseract.projectnaptha.com/)
- Inspired by this bot https://gist.github.com/kecebongsoft/1510198

## License

[LICENSE.md]()

                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/


