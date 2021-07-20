# WHMCS-TelegramNotify
Send WHMCS notifications to telegram

## Installation
1. Place the Telegram folder in your WHMCS installation (modules/notification/Telegram)
2. Create a bot with [BotFather](https://telegram.me/BotFather "BotFather"), and get the token.
3. Send a message to your new bot from the user/channel on which you want to receive notifications.
4. Go to this URL: https://api.telegram.org/bot[TOKEN]/getUpdates
(Replace[TOKEN] with your bot token)
5. Get your chat ID
6. Go to your WHMCS administration panel, Setup > Notifications, click on the Configure button under Telegram, and put your bot token and chat ID, you should receive a message "Connected with WHMCS", otherwise, check your chat ID and token.


