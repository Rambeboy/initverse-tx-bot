# INITVERSE TX BOT

The Initverse Bot is a powerful tool designed for interacting with Initverse Incenves Testnet networks. This bot automates daily transaction processes, enabling users to perform actions such as daily swap and daily check in interactions seamlessly. Additionally, it provides a built-in smart contract deployment feature, making it an ideal solution for you to do your testnet airdrop.

## PREREQUISITE

- Git
- Node JS (v22)

## INITVERSE INCENTIVE TESTNET AIRDROP

Initverse Incentivized Testnet

Reward: Points > $INI Tokens

[Link](https://candy.inichain.com/?invite=88X0E3WSMODCIMTJ0CQ4RO65Y)
- Connect your metamask wallet (Burner)
- Complete all task on ([TASK PAGE](https://candy.inichain.com/taskOperate))
- Done

[Details](https://inichain.gitbook.io/initverse-network/testnet-actvity/step-by-step-guide)

**LFG**

## BOT FEATURE

- Multi Account 
- Support PK & SEED
- TX Daily (Wrap Unwrap INI/WINI)
- TX Daily (SELF TRANSFER)
- Swap Daily (INI to USDT)
- Daily Check In
- Deploy Smart Contract


## SETUP & CONFIGURE BOT

### LINUX

1. Clone project repository
   ```
   git clone https://github.com/Rambeboy/initverse-tx-bot.git && cd initverse-tx-bot
   ```
2. Install Dependencies & Setup Accounts
   ```
   npm install && npm run setup
   ```
3. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
4. Configure the bot config
    ```
   nano config/config.js
    ```
5. To run Auto TX
   ```
   npm run start
   ```
6. To run Contract Deployer
   ```
   npm run deploy
   ```
   
### WINDOWS

1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repo
   ```
   git clone https://github.com/Rambeboy/initverse-tx-bot.git
   ```
   and cd to project dir
   ```
   cd initverse-tx-bot
   ```
3. Install Dependencies & Setup Accounts
   ```
   npm install && npm run setup
   ```
5. Navigate to `initverse-tx-bot` directory. 
6. Navigate to `accounts` directory.
7. Now open `acccounts.js` and setup your accounts. 
8. Now Back to `initverse-tx-bot` directory and Navigate to `config` directory and adjust the `config.js` as needed.
9.  Back to `initverse-tx-bot` directory.
10. To start the app open your `Command Prompt` or `Power Shell`
11. To run auto Tx Bot
    ```
    npm run start
    ```
12. To run Smart Contract Deployer
    ```
    npm run deploy
    ```

## UPDATE BOT

To update bot follow this step :
1. Run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   If error run
   ```
   git stash && git pull
   ```
2. Run
   ```
   npm update
   ```
3. Start the bot
4. If any eror happen check `log/app.log`


## IMPORTANT NOTE (READ IT THIS IS NOT DECORATION)
DWYOR & Always use a new wallet when running the bot, I am not responsible for any loss of assets.

If any error regarding SQL, try to delete `database.db` first.

## LICENSE

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

