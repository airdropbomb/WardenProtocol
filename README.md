# Warden Protocol BOT
Warden Protocol BOT

- Register Here : [Warden Protocol](https://app.wardenprotocol.org/referral?code=QVZJ2)
- Sign Up With New EVM Wallet
- Use Code `QVZJ2`

## Features

  - Auto Get Account Information
  - Auto Run With [Proxyscrape Free Proxy](https://proxyscrape.com/free-proxy-list) - `Choose 1`
  - Auto Run With Private Proxy - `Choose 2`
  - Auto Run Without Proxy - `Choose 3`
  - Auto Rotate Invalid Proxies - `y` or `n`
  - Auto Perform Daily Check-In Activity
  - Auto Perform Playing Game Activity
  - Auto Perform Chat With AI Activity
  - Multi Accounts

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/airdropbomb/WardenProtocol.git && cd WardenProtocol
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

### Note: Check your eth-utils and eth-account libraries version first. If not same with version in requirements.txt, u must uninstall that library.
- **Check Library Version**
  ```bash
    pip show libary_name
  ```
- **Uninstall Library**
  ```bash
    pip uninstall libary_name
  ```
- **Install Library With Version**
  ```bash
    pip install libary_name==version
  ```

## Configuration

- **accounts.txt:** You will find the file `accounts.txt` inside the project directory. Make sure `accounts.txt` contains data that matches the format expected by the script. Here are examples of file formats:

  ```bash
    your_private_key_1
    your_private_key_2
  ```
- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```
