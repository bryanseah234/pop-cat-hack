# pop-cat-hack
code to auto click in the popcat game




<p align="left">
  <img src="https://lh3.googleusercontent.com/YPSZ9e1wW1z7cIyjkpQUqAdMzlgaPprj3_1n9tKesPfYR8U1nlxcsHFk8Dd-1XWa-ymskRLekQ=w640-h400-e365" />
</p>

## Disclaimer:
1. USE AT OWN DISCRETION
2. FOR EDUCATIONAL PURPOSES ONLY

## Instructions:
1. Copy and paste the code into the console of Chrome




> **KNOWN ISSUE:** Some reported that v3.0 might not working on a Mobile browser. I have written v3.1 for Mobile support and it's now under testing. You can get the script here and do let me know if the issue still persist: <a href="https://gist.github.com/jvloo/f52b7a264dcf81241182d31c94d1ef5c" target="_blank">clicker-v3.1-dev.js</a>

This is a JS auto-click script for <a href="https://popcat.click/" target="_blank">PopCat challenge</a> that directly bypass bot detection.

The script accesses the PopCat's Vue app instance directly and manipulate the key variables which contributes to click counter, spam counter and API call, so to ensure that:

1. You hit the max 800 clicks per 30s (according to the API rate limit)
2. You won't get marked as bot (100% works - Direct send clicks to API endpoint)

*‼️ MALAYSIA IS 2TH PLACE NOW ‼️ 🎉🎉 (at time of writing script)*

<img src="https://i.imgur.com/688fQrN.png">

## How to Use (Simple)

> **NOTICE:** Only 1 browser allowed per device. API rate limit is enforced per IP address.

1. Copy all content of the file: <a href="https://raw.githubusercontent.com/jvloo/popcat-clicker/main/clickbot-v3.min.js" target="_blank">clickbot-v3.min.js</a> *OR* <a href="https://raw.githubusercontent.com/jvloo/popcat-clicker/main/clickbot-v3-with-pop.min.js" target="_blank">clickbot-v3-with-pop.min.js</a> (with click counter)
2. Visit <a href="https://popcat.click/" target="_blank">https://popcat.click/</a>
3. Tap `F12` to open browser devtool & navigate to "Console" tab
4. Tap `Ctrl` + `v` to paste all content into console
5. Tap `Enter` to run the script
6. (Optional) Navigate to "Network" tab to check if your API request accepted or rejected (in red text)

<img src="https://i.imgur.com/UFYw0hw.png">

## How to Use (Advanced - Python version)

> **NOTICE:** Only 1 browser allowed per device. API rate limit is enforced per IP address.

1. Make sure you have install Python 3 with PIP (Python package manager)
2. Install Selenium package via PIP
3. <a href="https://github.com/jvloo/popcat-clicker/archive/refs/tags/v2.zip" target="_blank">Click here to download script</a>
4. Extract files & double click **"clickbot-v2.py"** to run

## About Popcat Rules

- API rate limit = 800 clicks per 30 seconds (So far I can't bypass this)
- If you send 800 clicks or above, system will only record 800 clicks & spam score +1
- If you hit 10 spam scores, system will mark you as bot & no further clicks will be sent to API

> Clearing the bot cookie won't work at script level, because PopCat also set `this.bot` variable to true,
> unless you clear the cookie & refresh the browser (reload the script).
> The bot cookie is only useful for them to record you as bot when you refresh the browser.
> 
> You may check the script extracted from <a href="https://github.com/jvloo/popcat-clicker/blob/main/popcat-app.html" target="_blank">PopCat's App.vue (line 152)</a>. 



> Original author: Xavier Loo (https://github.com/jvloo/popcat-clicker)
