# XOS Testnet Automation BOT

Power up your journey on the **XOS Testnet** with full automation!  
Get your tasks done across wallets, swaps, faucets, and check-ins — hands-free. ⚡

- 🔗 Register Here: [XOS Testnet](https://X.ink/O0EX0O)
- 🔄 [Faucet](https://faucet.x.ink/)
- 💱 [DEX](https://dex.x.ink/swap)

---

## 🧰 Features

- ✅ Auto Account Info Detection  
- ✅ Proxy Support  
   - Public Proxy via [Proxyscrape](https://proxyscrape.com/free-proxy-list) (Option 1)  
   - Private Proxy (Option 2)  
   - Run Without Proxy (Option 3)  
- 🔁 Proxy Rotation (Yes / No)  
- 🧠 Auto Check-In Claim  
- 🎟️ Auto Perform Draw  
- 💧 Auto Claim Faucet *(Requires 2Captcha Key)*  
- 🔄 Auto Wrap & Unwrap  
- 🔀 Auto Make Swap Transactions  
- 👥 Multi-Account with Threading

---

## 📦 Requirements

- Python 3.9+  
- pip  
- 2captcha API key *(optional but needed for faucet)*

---

## 🔧 Installation

1. **Clone the Repository**
```bash
git clone https://github.com/DalleDai/XOS-Automation-BOT.git
cd XOS-Automation-BOT
````

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

> 🔍 *Note:* Check `web3`, `eth-account`, and `eth-utils` versions. If incompatible, uninstall and install required versions:

```bash
pip show web3
pip uninstall web3
pip install web3==VERSION
```

---

## ⚙️ Configuration

* `nano accounts.txt` — Add your private keys, one per line:

```txt
your_private_key_1
your_private_key_2
```

* `nano 2captcha_key.txt` — Add your [2Captcha](https://2captcha.com) key (optional but required for faucet):

```txt
your_2captcha_api_key
```

* `nano proxy.txt` — Add your proxies:

```txt
ip:port
http://ip:port
http://user:pass@ip:port
```

---

## 🚀 Run the Bot

```bash
python bot.py
# or
python3 bot.py
```

---

## Happy Farming! 🚀🌾

*Brought to you by [CryptoDai3](https://t.me/cryptodai3) X [YetiDAO](https://t.me/YetiDAO)*

---

## ☕ Buy Me a Coffee

* **EVM:** `0xd07Ac11e9b2590d3788Cd9e2f833034C9555178e`

---

## 🔒 Safety & Support

### ⚠️ Important Disclaimer

* **Testnet Only** – This tool is designed for testnet environments only
* **No Liability** – Use at your own risk. Developers assume no responsibility
* **DYOR** – Always do your own research before using any automation tools

### 🛡️ Security Best Practices

* 🔐 Never use Main wallets
* 🚫 Never expose sensitive credentials
* 📜 Always review code before execution
* 💸 Use burner wallets with test tokens only

---

### 🙌 Support Our Work

Love this tool? Help us improve:

* ⭐ Star the repository
* 🔗 Share with your farming community
* 💎 Use our referral codes (where applicable)
* 💡 Contribute ideas and code

---

## 📝 License

This project is licensed under the MIT License.

---
Let me know if you also want a TG post or welcome banner for this bot!
```
