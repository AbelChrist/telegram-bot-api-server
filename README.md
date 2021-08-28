# Host your own telegram "local" api server on heroku

## Usage
1. Have a heroku account (register in here [heroku.com](https://signup.heroku.com))
2. Deploy the app [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/AbelChrist/telegram-bot-api-server)
3. set environment variables when asked or in settings->config vars->reveal config vars with key and value:
```.env
TELEGRAM_API_ID=xxx
TELEGRAM_API_HASH=xxx
```
Note: Replace the `xxx` with api_id and api_hash that was obtained from https://core.telegram.org/api/obtaining_api_id

