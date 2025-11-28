# Pop Cat Hack

An auto-clicker bot for the PopCat challenge game to maximize your clicks effortlessly.

<p align="left">
  <img src="https://camo.githubusercontent.com/8e4467f6fd6ee369611af4c0667afb6445e2fc6ba417f7140d13e7dea6b34a26/68747470733a2f2f692e696d6775722e636f6d2f676265756278442e6a7067" />
</p>

## Description

Pop Cat Hack is an automation tool designed for the viral PopCat clicking game (popcat.click). It provides multiple methods to automate clicking, including browser console scripts and Python-based Selenium automation. The tool sends up to 800 clicks per 30 seconds, respecting the game's API rate limits to avoid bot detection.

## Features

- JavaScript-based auto-clicker that runs directly in the browser console
- Optional click counter display to track your automation progress
- Python + Selenium automation script for headless browser automation
- Smart rate limiting to stay within the 800 clicks/30 seconds threshold
- Captcha token handling for seamless API communication

## Technologies Used

- Python 3
- Selenium WebDriver
- JavaScript (ES6+)
- jQuery
- Microsoft Edge WebDriver

## Installation

```bash
# Clone the repository
git clone https://github.com/bryanseah234/pop-cat-hack.git

# Navigate to project directory
cd pop-cat-hack

# Install dependencies (for Python/Selenium method)
pip install -r requirements.txt
```

## Usage

### Method 1: Browser Console (Simple)

```javascript
// Copy the contents of clickbot-v3.min.js or clickbot-v3-with-pop.min.js
// Then:
// 1. Visit https://popcat.click/
// 2. Press F12 to open browser devtools
// 3. Navigate to the "Console" tab
// 4. Paste the script and press Enter
// 5. Check the "Network" tab to verify API requests
```

### Method 2: Python + Selenium (Advanced)

```bash
# Run the Python script (requires Edge WebDriver)
python clickbot-v2.py
```

### PopCat Rules to Note

- API rate limit = 800 clicks per 30 seconds
- Sending 800+ clicks only records 800 and adds a spam score
- Reaching 10 spam scores marks you as a bot

## Demo

Visit [https://popcat.click/](https://popcat.click/) to see the game in action.

## Disclaimer

1. FOR EDUCATIONAL PURPOSES ONLY
2. USE AT YOUR OWN DISCRETION

> Note: Only 1 browser allowed per device. API rate limit is enforced per IP address.

## License

MIT License

---

**Author:** <a href="https://github.com/bryanseah234">bryanseah234</a>

> Original author: Xavier Loo (https://github.com/jvloo/popcat-clicker)
