# 🎨 Discord AI Image Generator Bot

A Discord bot that generates AI images using Stable Diffusion.

Users can generate images directly inside Discord using a simple slash command.  
The bot sends the prompt to a Stable Diffusion API and returns the generated image.

---

# Features

- AI image generation from text prompts
- Discord slash command `/generate`
- Works with Stable Diffusion APIs
- Lightweight Python bot
- Easy installation
- Clean project structure

---

# Example Usage

Inside Discord run:

`/generate prompt: dragon with a flaming sword`

The bot will generate an image and post it in the channel.

---

# Project Structure

discord-ai-image-bot/

bot.py  
config.py  
requirements.txt  
.env.example  
.gitignore  

utils/  
 image_api.py  

scripts/  
 setup.sh  

README.md  

---

# Requirements

- Python 3.9 or newer
- Discord bot token
- Stable Diffusion API endpoint

---

# Installation

Clone the repository

```
git clone https://github.com/YOURNAME/discord-ai-image-bot.git
cd discord-ai-image-bot
```

Create a virtual environment

```
python3 -m venv venv
```

Activate the environment

Linux / macOS

```
source venv/bin/activate
```

Windows

```
venv\Scripts\activate
```

Install dependencies

```
pip install -r requirements.txt
```

---

# Configuration

Copy the environment file

```
cp .env.example .env
```

Edit `.env` and add your configuration

```
DISCORD_TOKEN=your_discord_bot_token
API_URL=https://your-stable-diffusion-api/generate
```

---

# Running the Bot

Start the bot

```
python bot.py
```

---

# Commands

Generate an image

```
/generate prompt: futuristic cyberpunk city
```

---

# How It Works

1. A user runs `/generate` inside Discord  
2. The bot sends the prompt to the Stable Diffusion API  
3. The API generates an image  
4. The bot sends the generated image back to Discord  

---

# Dependencies

The project uses the following Python libraries

- discord.py
- requests
- python-dotenv

They are installed automatically using

```
pip install -r requirements.txt
```

---

# License

MIT License

You are free to modify and distribute this project.

---

# Support

If you like the project, consider starring the repository on GitHub.
