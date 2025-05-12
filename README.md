
# 💥 Raydium Volume Bot 🚀

Boost the volume of your **SPL tokens** on **Raydium** with this powerful bot!  
By distributing SOL across multiple wallets and performing automated buys and sells, this bot keeps your token’s volume high and liquidity active on the platform.

---

## 📞 **Contact Information**

If you have any questions or need support, feel free to reach out!  
**Telegram**: [@thegreatkey](https://t.me/thegreatkey)

---

## ⚡ **Features**  
- **💳 Automated Wallet Creation**: Create multiple wallets for automated token buys and sells.
- **💰 SOL Distribution**: Distribute SOL across the wallets to fund the buy/sell operations.
- **🔄 Endless Buy/Sell Cycles**: Continuous trading with distributed wallets for increasing liquidity.
- **⚙️ Customizable Parameters**: Fine-tune buy amounts, sell intervals, wallet distribution, and more.

---

## 🛠️ **Installation & Setup**

Follow these steps to get started:

### 1. Clone the repository:
```bash
git clone https://github.com/marccanlas/Raydium-volume-bot.git
cd Raydium-volume-bot
```

### 2. Install dependencies:
```bash
npm install
```

### 3. Configure environment variables:

- Rename `.env.example` to `.env`  
- Set the following environment variables:
  - RPC & WSS  
  - Main wallet's secret key  
  - Jito Auth Keypair

### 4. Run the bot:
```bash
npm run start
```

---

## 🏅 **Version 1** (Free Version)

### 🚨 **What’s Included in Version 1**:
- **Basic functionality** to distribute SOL and automate buying and selling actions with new wallets.
- **Free to use** for those looking to experiment or start with basic volume boosting.

---

## 🛠️ **Version 2 (Private Version)**

Version 2 has been developed with **advanced features**, but it's kept private for now. Stay tuned for updates or reach out for more information.

---

## 🔄 **Version 2 Improvements**  
Here’s how **Version 2** improves over **Version 1**:

- **❌ Repetitive Trading**: Version 1 used a single wallet for buy/sell, making it easy to detect on DexScreener.
- **✅ New Wallet Creation**: After each buy/sell cycle, SOL is transferred to a new wallet, avoiding repetitive actions.
  
- **❌ No Increase in Makers**: Version 1 didn’t create new pool makers.
- **✅ Maker Increase**: New wallets are created with every cycle to increase pool makers, helping with liquidity.

- **❌ Tokens Left Unfinished**: Unfinished tokens were left in the wallet.
- **✅ Smart Gathering**: Tokens are sold before gathering, ensuring only SOL is gathered.

- **❌ Equal Buy/Sell Actions**: Only one buy and one sell created unbalanced trading pressure.
- **✅ More Buy Actions**: The bot now randomly buys more than it sells, creating additional buy pressure.


## 🚀 **Version 3 - High-Speed, High-Volume**  
**Version 3** takes volume boosting to the next level. It's designed for **massive transactions in a short period**.  
🔹 **500 transactions per minute**  
🔹 **20 transactions per second**  
🔹 No repeated wallet makers  
🔹 You can easily reach **1 million transactions per hour** by scaling up the volume!

## 💡 **Why Choose Raydium Volume Bot?**

- **💪 Boost Token Volume**: Perfect for increasing liquidity and trading volume on Raydium.
- **⚡ Speed & Efficiency**: With **Version 3**, you can handle massive transaction volumes in a fraction of the time.
- **🔐 Secure**: Full control over wallets and your trading strategy—your funds are safe!
- **🛠️ Customizable Settings**: Fine-tune all aspects of the bot to fit your strategy and needs.


## 🚀 **Get Started Today!**  
Clone the repo, run the bot, and start boosting your token’s volume and liquidity on Raydium!

Feel free to reach out for help, enhancements, or to learn more about the bot's features. Happy trading! 🌟

