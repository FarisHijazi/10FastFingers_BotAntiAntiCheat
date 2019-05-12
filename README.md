# 10FastFingers.com Bot with AntiAntiCheat, What is this?

![Hackit button](/screenshots/Screenshot_1.png)

See [demo Youtube video here](https://youtu.be/k-Z25PRZY14)

## What's the website about

[10fastfingers](www.10fastfingers.com) is a speed typing website where you can test your typing speed.

## How this came to be

Me being bored and busy with other important tasks (**EXAMS**), I decide that it'd be best to ignore them and create a bot, how responsible.

----

## What it does

This bot will type in the words for you as fast as you want.

![typing test h@kt](/screenshots/10ff-hacked.gif)

Now if you choose a really high speed (like 300 words per minute),
[10fastfingers](www.10fastfingers.com) will ask you to complete an [anti-cheat test](https://10fastfingers.com/anticheat/view/1/1),
where there is an image with text in it, rather than having the raw text, this is an anticheat measure, and this is an anti-anticheat script.

![anticheat h@kt](/screenshots/10ff-OCR-hackerman.gif)

The script can also deal with this, using OCR [tesseract.js](https://tesseract.projectnaptha.com/)

## How to use

There are two ways to use this script, either by:

- pasting it in the browser's console (the simpler and quicker option)

or

- installing it as a userscript.

### Method1 (Simple): Pasting to the console

1. Copy the entire script from here [here](10fastfingers_bot_antianticheat.user.js) or [RAW link](/../../raw/master/10fastfingers_bot_antianticheat.user.js) (`CTRL+A`, `CTRL+C`)
2. Paste in the [10fastfingers](www.10fastfingers.com) page,  
    - open the developer console in Google Chrome `CTRL+SHIFT+J`, (you should be on the `console` tab)
    - Paste (CTRL+V), then hit (ENTER)
3. Press the `HACKIT` button that was added to the page

### Method2: Downloading a UserScript client (Tampermonkey/Greasemonkey)
1. Download a UserScript browser extension like [Tampermonkey](https://www.tampermonkey.net/)
2. Install the script (click the [RAW link](/../../raw/master/10fastfingers_bot_antianticheat.user.js), you should be redirected to the install page, otherwise you don't have a UserScript client installed)
3. Reload your [10fastfingers](www.10fastfingers.com) page (CTRL+R does NOT work, you must re-enter the address in the address bar)  
    Press the `HACKIT` button that was added to the page


![anticheat resulting score](/screenshots/Screenshot_2.png)

## Details and limitations

For the typing test, there are only 360 words, so the max possible speed is 360 in one minute, this is because of how the website is built, the didn't think anyone would go over 360 words per minute.

For the anticheat test, I have gotten up to sub-1000wpm (about 966), unlocking about 1200wpm.

I need to mention that the anticheat test will take a long time the first time, this is because `Tesseract` needs to download its weights. The following times it will use the cached dataset that it just downloaded.

![anticheat resulting score](/screenshots/Screenshot_10fastfingers_antianticheat_2.png)

## Notices

- This script is made purely for educational purposes
- This script uses [Tesseract.js](https://tesseract.projectnaptha.com/)
- Inspired by this bot https://gist.github.com/kecebongsoft/1510198

## License

[LICENSE.md]()

                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/


