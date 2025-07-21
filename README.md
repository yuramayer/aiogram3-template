# Telegram Bot Template (aiogram 3)

This project is **template** for building Telegram bots
using **aiogram 3**

It features:

- Structured layout for scalable bots
- Environment-based configuration
- Minimal dependencies for easy deployment

## 📁 Project Structure

```plaintext
.
├── .env              # Environment variables
├── app.py            # Entry point
├── bot.py            # Bot and dispatcher setup
├── config/           # Environment loader
├── handlers/         # All your command/message handlers
├── utils/            # Startup and helper functions
├── requirements.txt  # Dependencies
└── README.md
```

## ⚙️ Environment Configuration (`.env`)

All secrets are stored in the `.env` file. You must create it manually:

```env
TEST_BOT_TOKEN=your_test_token_here
PROD_BOT_TOKEN=your_prod_token_here
ADMINS=12345678,98765432
STAND=LOCAL
```

- `TEST_BOT_TOKEN`: Bot token for testing (e.g. from BotFather)
- `PROD_BOT_TOKEN`: Production token
- `ADMINS`: Comma-separated list of Telegram user IDs with admin rights
- `STAND`: One of `LOCAL` or `PROD`

## 📦 Dependencies

![aiogram](https://img.shields.io/badge/aiogram-3.x-blueviolet?logo=telegram&logoColor=white)  ![python-dotenv](https://img.shields.io/badge/python--dotenv-env%20loader-green?logo=dotenv&logoColor=white)  

Install the dependencies with pip:

```bash
pip install -r requirements.txt
```

## 🚀 Running the Bot

To run the bot locally:

```bash
python app.py
```

Make sure:

- Your virtual environment is activated
- `.env` is correctly configured

## 📝 License

This project is MIT licensed. Feel free to fork and adapt for your needs!
