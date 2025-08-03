# Telegram Instagram Info Bot

This is a basic Telegram bot built with [Aiogram](https://docs.aiogram.dev) and [Instaloader](https://instaloader.github.io/) to fetch public Instagram profile information.

## Features

- Start with `/start` command
- Send any Instagram username to get:
  - Followers count
  - Followees count
  - Total posts count
- Inline button to refresh data

## How it works

1. The user sends an Instagram username.
2. The bot fetches the public profile info using Instaloader.
3. The bot displays the number of followers, followees, and posts.
4. The user can tap the `♻️Yangilash` button to update the info.

## Requirements

- Python 3.10+
- Aiogram 3.x
- Instaloader

## Installation

1. Clone the repository.
2. Install the dependencies:
