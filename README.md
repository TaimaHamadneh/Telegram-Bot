# Telegram Bot (Marco-Polo) 🤖

A simple Telegram bot built with Node.js and Express.
It listens for incoming messages and replies **"Polo!!"** whenever a message contains the word **"marco"**.

---

##  Features

* Receives Telegram webhook updates
* Parses incoming messages
* Responds automatically when "marco" is detected

---

##  Technologies Used

* Node.js
* Express
* Axios
* Body-parser

---

##  Installation

1. Clone the repository:

```bash
git clone https://github.com/TaimaHamadneh/Telegram-Bot
cd my-telegram-bot
```

2. Install dependencies:

```bash
npm install
```

---

##  Running the App

Start the server:

```bash
node index.js
```

You should see:

```
Telegram app listening on port 3000!
```

---

##  Setting Up Telegram Webhook

Replace `<YOUR_BOT_TOKEN>` with your bot token and run:

```bash
curl.exe -F "url=https://your-domain.vercel.app/api/new-message" https://api.telegram.org/bot<YOUR_BOT_TOKEN>/setWebhook
```

---

##  How It Works

1. Telegram sends updates to your webhook
2. The app checks if the message contains "marco"
3. If true → replies with:

```
Polo!!
```

