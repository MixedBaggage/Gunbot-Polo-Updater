# Gunbot-Polo-Updater
Updates Gunbot 4.0.5+ config.js for poloniex coins by volume

v4+ NOTE: Updater PHP file, PoloAPI.php, and BittrexAPI.php ALL required and must all be in SAME folder.

This uses Poloniex and Bittrex PHP API to automatically update config.js to bot top volume coins or sell off coins with reduced volume.

Instructions:

For PoloTA Version:
Download and enable Trader PHP extension. 

Windows binaries: http://windows.php.net/downloads/pecl/releases/trader/0.4.0/
<br/>
Linux: https://pecl.php.net/package/trader

1) Install PHP (php7 recommended)

2) Enable cUrl and openssl PHP Extensions in php.ini 

3) Create a NEW poloniex/bittrex API Key

4) Set your key and secret in the .php file.

5) Set configuration based on comments.

6) Schedule to run using cron or task scheduler. Recommended 90 minute intervals.

For exemptions. Set the configuration for your manual coins in your config.js. Add those coin names to manualconfig section to leave your manual configurations.<br/>

If you like my work, I don't drink sooo buy me a Starbucks?<br/>
<b>BTC:</b> 1EbMRKN6eF8DJMA114E8Hx6JWyzX8YvN65 <br/>
<b>ETH:</b> 0xB0cF532D96Ca3cf53484FA5c788A1627568Bb942

Not my code, I have just edited file to work with 5.0.5.
