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

- Copy the entire script from here [here](10fastfingers_bot_antianticheat.user.js) or [RAW link](raw/master/10fastfingers_bot_antianticheat.user.js) (simple CTRL+A, CTRL+C)
- Navigate to your [10fastfingers](www.10fastfingers.com) page
- Open the developer console in Google Chrome (CTRL+SHIFT+J)
- Paste (CTRL+V), then hit (ENTER)
- Press the `HACKIT` button that was added to the page

### Method2: Downloading a UserScript client
- Download a UserScript client like [Tampermonkey](https://www.tampermonkey.net/)
- Then open the script and install it by clicking the [RAW link](raw/master/10fastfingers_bot_antianticheat.user.js)
- Navigate to your [10fastfingers](www.10fastfingers.com) page
- Reload the page (CTRL+R does NOT work, you must re-enter the address in the address bar)
- Press the `HACKIT` button that was added to the page


## Notices

- This script is made purely for educational purposes
- This script uses [Tesseract.js](https://tesseract.projectnaptha.com/)
- Inspired by this bot https://gist.github.com/kecebongsoft/1510198

## License

[LICENSE.md]()

                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/


