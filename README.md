# pop-cat-hack
code to auto click in the popcat game

<p align="left">
  <img src="https://camo.githubusercontent.com/8e4467f6fd6ee369611af4c0667afb6445e2fc6ba417f7140d13e7dea6b34a26/68747470733a2f2f692e696d6775722e636f6d2f676265756278442e6a7067" />
</p>

## Disclaimer:
1. USE AT OWN DISCRETION
2. FOR EDUCATIONAL PURPOSES ONLY
3. Only 1 browser allowed per device. API rate limit is enforced per IP address.

## Instructions (simple):
1. Copy all content of the file: <a href="https://raw.githubusercontent.com/bryanseah234/popcat-clicker/main/clickbot-v3.min.js" target="_blank">clickbot-v3.min.js</a> *OR* <a href="https://raw.githubusercontent.com/bryanseah234/popcat-clicker/main/clickbot-v3-with-pop.min.js" target="_blank">clickbot-v3-with-pop.min.js</a> (with click counter)
2. Visit <a href="https://popcat.click/" target="_blank">https://popcat.click/</a>
3. Tap `F12` to open browser devtool & navigate to "Console" tab
4. Tap `Ctrl` + `v` to paste all content into console
5. Tap `Enter` to run the script
6. Navigate to "Network" tab to check if your API request accepted or rejected (in red text)

## Instructions (advanced)
1. Make sure you have install Python 3 with PIP (Python package manager)
2. Install Selenium package via PIP
3. <a href="https://github.com/bryanseah234/popcat-clicker/archive/refs/tags/v2.zip" target="_blank">Click here to download script</a>
4. Extract files & double click **"clickbot-v2.py"** to run

## Popcat Rules
- API rate limit = 800 clicks per 30 seconds (So far I can't bypass this)
- If you send 800 clicks or above, system will only record 800 clicks & spam score +1
- If you hit 10 spam scores, system will mark you as bot & no further clicks will be sent to API

> Original author: Xavier Loo (https://github.com/jvloo/popcat-clicker)
