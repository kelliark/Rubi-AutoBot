# Rubi Click Multi-Account Mining Bot

A powerful bot for automatically mining gems on the Rubi Click platform with support for multiple accounts and proxy rotation.

## Register here: 

1st: Download their app : [Rubi - Apps on Google Play](https://play.google.com/store/apps/details?id=com.nemoholding.android.rubi) 
if you're using IOS just type Rubi on your AppStore, I think that's the app is called

2nd: Use Code: **FARMER**

3rd: Add me to your Trust Circle
DONE

## Features

- **Multi-Account Support**: Mine with multiple accounts simultaneously
- **Proxy Support**: Rotate through proxies to prevent IP bans
- **Real-Time Dashboard**: Monitor all your mining operations in one place
- **Automatic Token Refresh**: Keeps your sessions active
- **Error Handling**: Robust error recovery mechanisms
- **Colorful Console UI**: Easy-to-read status updates

## Requirements

- Python Latest Version
- Git
- Dependencies:
  - requests
  - colorama
  - pysocks
  - cryptography

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/kelliark/Rubi-AutoBot
   cd Rubi-AutoBot
   ```

2. Install required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up your account information:
   - Create an `accounts.txt` file with your accounts in format: `username:password`
   - Optionally create a `proxies.txt` file with proxies (one per line)

## Usage

Run the bot with:

```
python main.py
```

The bot will:
1. Log in to all your accounts
2. Start mining operations
3. Display a real-time dashboard showing mining status
4. Periodically refresh tokens to maintain session validity

Press `Ctrl+C` to safely stop all mining operations.

## Dashboard

The dashboard displays:
- Active miners count
- Total gems mined
- Per-account statistics:
  - Current gem balance
  - Mining speed
  - Remaining mining time
  - IP/Location information

## Configuration

### Accounts Format
In `accounts.txt`:
```
username1:password1
username2:password2
```

### Proxies Format
In `proxies.txt`:
```
http://username:password@ip:port
ip:port
```

## Disclaimer

Use at your own risk, all risk are borne with user.
