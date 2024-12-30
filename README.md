# Discord Active Developer Badge Setup

This guide will help you get the **Active Developer** badge from Discord by following the instructions step-by-step. If you're new to Discord bot development, this is a great way to get started!

---

## Prerequisites

- **A Discord account**
- **A Discord server** (You can create a new one for testing)
- **A Replit account** (for running the bot)
- **A Discord bot token** (You’ll get this when you create the bot on the Discord Developer Portal)

---

## Steps to Get the Active Developer Badge

### 1. **Create a New Application and Bot on Discord**

- Go to the [Discord Developer Portal](https://discord.com/developers/applications).
- Log in with your Discord account and click on **"New Application"**.
- Name your application and click **"Create"**.
- In the left sidebar, select the **"Bot"** tab and click on **"Add Bot"**.
- **Important**: Click **"Reset Token"** to generate your bot's token. **Save this token**, as you'll use it later.

---

### 2. **Set Up the Bot Using Replit**

1. Clone this repository by clicking the badge below:

   [![Run on Replit](https://replit.com/badge/github/hackermondev/discord-active-developer-badge)](https://replit.com/new/github/hackermondev/discord-active-developer-badge)

2. You will be redirected to Replit, and it may ask you to sign in. You can register using Google or GitHub.

3. Once you're in Replit, the code will be automatically cloned into your workspace.

---

### 3. **Run the Bot**

1. Open the `bot.py` file in Replit. It’s a simple bot template.
   
2. **Paste Your Token**:
   - In the `bot.py` file, find the line `bot.run('YOUR_BOT_TOKEN')`.
   - Replace `'YOUR_BOT_TOKEN'` with the bot token you copied earlier from the Discord Developer Portal.

3. **Run the Bot**:
   - Click the **green "Run"** button at the top of the Replit interface.
   - The bot will start running, and you will see a message in the console like `Logged in as <bot_name>`.
   - The bot will now be online!

---

### 4. **Invite the Bot to Your Discord Server**

1. Go back to the **Discord Developer Portal**.
2. In your application’s settings, go to the **OAuth2** tab.
3. Under **OAuth2 URL Generator**, select the following:
   - **Scopes**: `bot`
   - **Bot Permissions**: `Send Messages` and any other permissions your bot needs.
4. Copy the generated URL and paste it into your browser to invite the bot to your Discord server.

---

### 5. **Verify the Bot is Working**

1. In your Discord server, go to any text channel.
2. Type `/ping` and press **Enter**.
3. The bot should reply with "Pong!", indicating it's working properly.

---

### 6. **Enable Community on Your Server**

1. If you don’t already have a community-enabled server, create a new server for testing purposes.
2. Enable **Community** by going to **Server Settings > Community**.
3. This step is required for your application to qualify for the Active Developer Badge.

---

### 7. **Apply for the Badge**

1. After your bot is working, visit the [Discord Active Developer page](https://discord.com/developers/active-developer).
2. Register your information and follow the instructions. If you're not immediately eligible, it can take up to 24 hours for Discord to mark you as eligible.

---

### 8. **Congratulations! 🎉**

Once you're approved, you will receive the **Active Developer Badge** on your Discord profile!

---

## Notes

- **Replit Cloud Hosting**: You don't need to keep the Replit tab open 24/7. Run the bot whenever you need it.
- **Eligibility**: Make sure your **"Use data to improve Discord"** setting is enabled under **User Settings > Privacy & Safety**. If this setting is off, you won’t be eligible for the badge.
- **Token Security**: Never share your bot's token publicly! If your token is exposed, regenerate it immediately in the Discord Developer Portal.

---

## Support

If you encounter any issues during setup, please feel free to:

- [Open a GitHub issue](https://github.com/hackermondev/discord-active-developer-badge/issues).
- Join our **[support Discord server](https://discord.gg/M5MSE9CvNM)** and ping me in the `#general` channel for assistance.

---

## Contributing

If you find any issues or have suggestions to improve this setup, feel free to fork this repository and create a pull request. Your contributions are welcome!

---

### Star the Repo ⭐

If you successfully get the Active Developer Badge, please **star** this repository to help others find it and use it. Feel free to join the [Discord server](https://discord.gg/M5MSE9CvNM) for additional help and updates.

---

Happy coding and enjoy your **Active Developer Badge**! 🎉🚀
