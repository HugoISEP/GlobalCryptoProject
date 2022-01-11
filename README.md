# GlobalCryptoProject

Global project that combines crypto trading bot and a separate API.
The project works with FTX exchanger

## Setup

> Clone the project with git clone and add the flag **--recurse-submodules** in order to load the submodules

> <u>Tips:</u> To pull the project and submodules run ```git config submodule.recurse true```

> Add a **config.ini** file in the root of the project with the format:
```
[DEFAULT]
api_key = <YOUR FTX API KEY>
api_secret = <YOUR FTX API SECRET>
subaccount_name = <YOUR SUB ACCOUNT>
bot_base_url = <YOUR_BOT_BASE_URL>
[AUTHENTICATION]
API_KEY = <YOUR_API_KEY>
API_KEY_NAME = <YOUR_API_KEY_NAME>
```

## Start the project

```docker-compose up -d```
