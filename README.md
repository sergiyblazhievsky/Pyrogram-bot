# Pyrogram Bot

A Telegram bot built with Pyrogram.

## Description

Training in Pyrogram - This project serves as a learning and training ground for building Telegram bots using the Pyrogram library.

## Requirements

- Python 3.8 or higher
- A Telegram API key (API ID and API Hash) from [my.telegram.org](https://my.telegram.org)

## Installation

1. Clone this repository:
```bash
git clone <repository-url>
cd Pyrogram-bot
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On Linux/Mac:
     ```bash
     source venv/bin/activate
     ```

4. Install dependencies:
```bash
pip install -r requirements.txt
```

## Configuration

1. Get your API credentials from [my.telegram.org](https://my.telegram.org)
2. Create a `.env` file (or configure directly in code):
```env
API_ID=your_api_id
API_HASH=your_api_hash
BOT_TOKEN=your_bot_token  # If using a bot account
```

## Usage

Run the bot:
```bash
python main.py
```

## Project Structure

```
Pyrogram-bot/
├── main.py              # Main entry point
├── requirements.txt     # Python dependencies
├── README.md           # Project documentation
└── .gitignore          # Git ignore rules
```

## Features

- Basic Pyrogram bot setup
- Ready for extension and customization

## Development

This is a training project for learning Pyrogram. Feel free to extend it with:
- Command handlers
- Message filters
- Database integration
- Webhook support
- And more!

## Resources

- [Pyrogram Documentation](https://docs.pyrogram.org/)
- [Pyrogram GitHub](https://github.com/pyrogram/pyrogram)
- [Telegram Bot API](https://core.telegram.org/bots/api)

## License

This project is for educational purposes.
