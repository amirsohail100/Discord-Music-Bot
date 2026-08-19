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
   ```bash
   git clone https://github.com/amirsohail100/Discord-Music-Bot.git
   ```
2. Navigate to the project directory.
   ```bash
   cd Discord-Music-Bot
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Discord Bot Commands

Here is the complete list of available commands to control the music bot in your Discord server:

| Command  | Usage                 | Description                                                                   |
| :------- | :-------------------- | :---------------------------------------------------------------------------- |
| `!join`  | `!join`               | Connects the bot to your current voice channel.                               |
| `!play`  | `!play <YouTube_URL>` | Streams audio directly from the provided YouTube link into the voice channel. |
| `!leave` | `!leave`              | Stops the music playback and disconnects the bot from the voice channel.      |

### How to use:

1. Join any voice channel in your Discord server.
2. Type `!join` in any text channel to bring the bot into your voice channel.
3. Type `!play <YouTube_URL>` to start listening to your track.
4. Type `!leave` when you want the bot to exit the voice channel.
