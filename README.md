# Soniclabs Arcade Testnet BOT

## Prerequisite
- Git
- Node JS
- $S TOKEN TESTNET FROM https://testnet.soniclabs.com/account
- Tokens on Your Sonic Arcade Accounts
- Play Plinko Game Once
- Play Whell Game Once
- Play Mines Game Once

## Soniclabs Arcade Incentive Testnet
#NEW AIRDROP

Sonic Labs ( Prev Fantom )

- Get Faucet : https://testnet.soniclabs.com/account
- Register : https://airdrop.soniclabs.com/?ref=9eu8kk
- Connect Wallet to Sonic Testnet
- Enter Access Code 
```
9eu8kk
```
- Click "Sonic Arcade" And Get You Token By Clickig on `Get some $TOKEN >`
- Connect Your Twitter > Follow Twitter > Complete Captcha > Get Token (REMEMBER TO CLAIM FAUCET WEEKLY)
- After You Get Your Token, Play All Game at Least Once
- Now You're Ready For BOT
- LFG


## BOT FEATURE

- Multi Account 
- Support PK
- Support Proxy
- Auto Play Arcade Game Daily


## Setup & Configure BOT

### Linux
1. clone project repo
   ```
   git clone https://github.com/dakochan212/soniclabsbot.git && cd soniclabsbot
   ```
2. run
   ```
   npm install
   ```
3. run
   ```
   cp -r accounts/accounts_tmp.js accounts/accounts.js && cp -r config/proxy_list_tmp.js config/proxy_list.js
   ```
5. configure your accounts
   ```
   nano accounts/accounts.js
   ```
6. configure the bot config
    ```
   nano config/config.js
    ```
7. configure the proxy (optional)
    ```
   nano config/proxy_list.js
    ```
8. to start the app run
    ```
    npm run start
    ```
   
## Update Bot

To update bot follow this step :
1. run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   if error run
   ```
   git stash && git pull
   ```
2. run
   ```
   npm update
   ```
2. start the bot


## NOTE

If you got `error still waiting random number` for so long time try to play manually to triggrer rpc `reinitiate` after that you can use bot again
