# 🚀 Bot Setup Instructions for Termux

Welcome to the **Termux Bot Setup Guide**! This guide will help you set up and run the bot on your mobile device using Termux. Follow each step carefully.

---

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Installation Steps](#installation-steps)
3. [Configuration Files](#configuration-files)
   - [`configs.json`](#1-configsjson)
   - [`datas.txt`](#2-datastxt)
   - [`wallets.txt`](#3-walletstxt)
   - [`proxies.txt`](#4-proxiestxt)
4. [Running the Bot](#running-the-bot)
5. [Contact and Support](#contact-and-support)

---

## Prerequisites

Make sure you have the following installed on your Termux app:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Run the following commands to install them:

```bash
pkg update && pkg upgrade
pkg install nodejs-lts
pkg install git
```

Check the versions:
```bash
node -v
npm -v
```

---

## Installation Steps

1. **Download and Extract the Bot Files:**

   Clone the bot repository or download it manually:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install Dependencies:**

   ```bash
   npm install user-agents axios colors p-limit https-proxy-agent socks-proxy-agent crypto-js ws uuid xlsx readline-sync
   ```

3. **Prepare Configuration Files:**
   Ensure all configuration files are set up correctly before running the bot (see [Configuration Files](#configuration-files) section).

---

## Configuration Files

### 1. `configs.json` - 📜 Adjust Bot Settings

Example configuration:

```json
{
  "timeZone": "en-US",
  "rotateProxy": false,
  "skipInvalidProxy": false,
  "proxyRotationInterval": 2,
  "delayEachAccount": [5, 8],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 100,
  "doTasks": true,
  "playGames": true,
  "referralCode": ""
}
```

### 2. `datas.txt` - 🗂️ User Data

```txt
query_id.../user...
query_id.../user...
```

### 3. `wallets.txt` - 💼 Wallet Addresses

```txt
abc...xyz
abc...xyz
```

### 4. `proxies.txt` - 🌐 Proxy List (Optional)

```txt
http://user:password@host:port
socks5://user:password@host:port
```

---

## Running the Bot

1. Navigate to the bot folder:

   ```bash
   cd /path/to/bot-folder
   ```

2. Run the bot:
   ```bash
   node bot
   ```

If you encounter permission issues, run:
```bash
chmod +x bot
```

---

## Contact and Support

- **Buy me a telegram account** [Here](https://t.me/KeoAirDropFreeNe/312/27801)

If you encounter any issues or have questions, feel free to reach out:

- **Contact:** [Contact Me](https://t.me/MeoMunDep)
- **Group:** [Join the Group](https://t.me/KeoAirDropFreeNe)
- **Channel:** [Visit the Channel](https://t.me/KeoAirDropFreeNee)

---

Enjoy using the bot on Termux! 🚀📱

