# Hexamon

A Telegram Pokémon bot built for fun, battle vibes, and quick Pokédex lookup.

<p align="center">
  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/25.png" alt="Pikachu" width="220" />
</p>

## Overview

Hexamon is a lightweight Telegram bot that lets users:

- search for Pokémon by name or ID
- view Pokémon details such as type, stats, and sprite
- catch random Pokémon
- build a small team
- explore the Pokédex directly from Telegram

This project is ideal as a starter bot for Pokémon fans, Telegram communities, or learning bot development with Python.

## Features

- /start — welcome message and bot introduction
- /pokemon <name-or-id> — fetch Pokémon information
- /random — show a random Pokémon
- /catch — catch a Pokémon from a random encounter
- /team — view your current team
- /help — list available commands

## Tech Stack

- Python 3
- python-telegram-bot
- requests
- PokéAPI

## Project Structure

```bash
Hexamon/
├── README.md
├── requirements.txt
├── bot/
│   ├── __init__.py
│   ├── config.py
│   ├── handlers.py
│   ├── pokemon_api.py
│   └── bot.py
├── .env.example
└── .gitignore
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/TheSunphis/Hexamon.git
cd Hexamon
```

2. Create a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate     # Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Create a `.env` file based on `.env.example`:

```env
TELEGRAM_BOT_TOKEN=your_telegram_bot_token_here
```

5. Run the bot:

```bash
python bot/bot.py
```

## Example Commands

```text
/start
/pokemon pikachu
/pokemon 25
/random
/catch
/team
/help
```

## Notes

This bot can be extended with:

- Pokémon battles
- leaderboard tracking
- item and move systems
- database storage for trainers
- custom inline keyboard menus

## License

This project is intended for educational and hobby use.

## Author

Built for the Hexamon project by TheSunphis.
