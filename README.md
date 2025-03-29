# Backup Script

## 📌 Overview
This script backs up critical data (databases, configs) from x-ui, Marzban, and Hiddify panels and sends it to Telegram via bot.

## 🚀 Quick Setup
```bash
bash <(curl -Ls https://github.com/j-mohebi/backuper/raw/main/backup.sh)

⚙️ Configuration Steps

    Bot Token

        Create bot via @BotFather

        Enter received token

    Chat ID

        Forward any message to @userinfobot

        Enter the numeric ID received

    Caption (Optional)

        Add backup description or skip

    Cron Schedule
    Format: minute hour
    Examples:

        30 6 → Daily at 6:30 AM

        0 0 → Every minute (testing)

    Panel Selection

        m → Marzban

        x → X-UI

        h → Hiddify

    Clear Existing Cronjobs?

        y → Remove old backups

        n → Keep existing

🔧 Post-Installation

    First backup runs immediately

    Subsequent backups follow cron schedule

    Files sent to specified Telegram chat

    Note: Tested on Ubuntu. May require adjustments for other OS.

❓ Troubleshooting

Report issues via GitHub Issues.
🤝 Contribution

Help improve translations or add OS compatibility!
