# GlobalCryptoProject

Global project that combines crypto trading bot and a separate API.
The project works with FTX exchanger

## Setup

> Clone the project with git clone and add the flag **--recurse-submodules** in order to load the submodules

> <u>Tips:</u> To pull the project and submodules run ```git config submodule.recurse true```

> Add a **config.ini** file in the root of the project with the format:
```
[DEFAULT]
api_key = <YOUR API KEY>
api_secret = <YOUR API SECRET>
subaccount_name = <YOUR SUB ACCOUNT>
bot_base_url = <YOUR_BOT_BASE_URL>
```

## Start the project

```docker-compose up -d```
