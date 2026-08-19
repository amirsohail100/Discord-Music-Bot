# Discord Music Bot Template

A simple, ready-to-use Discord music bot template built with Python.

## Prerequisites

- Python 3.8+
- FFmpeg installed on your system
- A Discord account and a created bot application

## Setup Instructions

### 1. Discord Developer Portal

1. Go to the [Discord Developer Portal](https://discord.com/developers/applications).
2. Create a new Application.
3. Navigate to the **Bot** tab.
4. Enable **Message Content Intent** under Privileged Gateway Intents.
5. Generate your **Token** and save it securely.
6. Invite the bot to your server using the OAuth2 URL Generator (give it `bot` and `Administrator` or appropriate Voice permissions).

### 2. Local Setup

1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
