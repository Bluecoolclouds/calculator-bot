# Calculator Bot

Example of Python Serverless Telegram bot to be used with <https://vercel.com>

## Steps

### Add env variable to vercel.com

Add your telegram bot token as `BOT_TOKEN` variable

### Register webhook

``` bash
curl "https://api.telegram.org/bot6556995841:AAGyBXCCbremRqXdHHuARfR3yaabQH78v-M/setWebhook?url=calculator-bot-one.vercel.app/api/webhook/"
```
