# Gemini Discord Bot

A multimodal Discord bot powered by Google Generative AI that can process images, audio, video, and text files.

## Features

- Multimodal AI interactions (text, images, audio, video)
- Image generation with multiple models
- Text-to-speech in multiple languages
- Music generation from prompts
- Custom personalities for users and servers
- Chat history management

## Setup

### Prerequisites

- Node.js v14+
- Discord Bot token
- Google API key

### Installation

```bash
git clone https://github.com/trulynotafan/bot.git
cd Gemini-Discord-Bot
npm install
```

Create `.env` file:
```env
DISCORD_BOT_TOKEN=your_discord_bot_token
GOOGLE_API_KEY=your_google_api_key
```

Start the bot:
```bash
npm start
```

## Commands

### Core Commands
- `/imagine [prompt] [model] [resolution]` - Generate images
- `/speech [language] [prompt]` - Text to speech
- `/music [prompt]` - Generate music
- `/respond_to_all` - Bot responds to all messages
- `/clear_memory` - Clear chat history
- `/settings` - User settings
- `/server_settings` - Server settings

### Admin Commands
- `/blacklist [user]` - Blacklist user
- `/whitelist [user]` - Remove from blacklist
- `/status` - Bot resource usage

## Configuration

Edit `config.json` to customize:
- Response format (embedded/normal)
- Default image model
- Personality settings
- NSFW filtering
- Server defaults

## Contributing

Fork the repo, create a branch, make changes, and submit a pull request.

## License

MIT License

---

**Author:** [@trulynotafan](https://github.com/trulynotafan)
