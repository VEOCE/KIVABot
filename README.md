# KIVA Network
KIVA Network BOT

- Register Here : [Kiva Network](https://kivanet.com/register.html?code=B7Z790)
- Use Code : B7Z790
- Send Email : `Verify Me` to `verify@kivanet.com` With Same Registered Email
- Login : `https://app.kivanet.com/`

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Complete Available Tasks
  - Auto Start Mining
  - Multi Accounts

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Installation

1. **COPY AND PASTE**
   ```bash
   git clone https://github.com/VEOCE/KIVABot.git
   cd KIVABot
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## ACCOUNTS SETUP
```bash
nano accounts.json
```
**Make sure `accounts.json` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
  [
      {
          "Email": "your_email_address 1",
          "Password": "your_password 1"
      },
      {
          "Email": "your_email_address 2",
          "Password": "your_password 2"
      }
  ]
  ```
## PROXY (OPTIONAL)
```bash
nano proxy.txt
```
 **Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```

