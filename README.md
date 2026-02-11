<h1 align="center">Discord has been banning my accounts for something unrelated to this selfbot this project is postponed but will continuely get updated and eventually released to GITHUB to get early access typ shi add my new disc "letshaveafoursome
"</h1>
<h4 align="center">A powerful Discord selfbot built from reverse-engineered components and community contributions.</h4>

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/Status-Alpha-yellow?style=for-the-badge" alt="Status">
  </a>
  <a href="https://www.python.org/downloads/">
    <img src="https://img.shields.io/badge/Python-3.8+-blue.svg?style=for-the-badge" alt="Python">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Discord-0.delay-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
  <br>
  <a href="#">
    <img src="https://img.shields.io/badge/Purpose-Educational-red?style=for-the-badge" alt="Educational">
  </a>
</p>

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Configuration](#-configuration) • [Contributing](#-contributing)

</div>

---

## ⚠️ IMPORTANT DISCLAIMER

> **This project is for EDUCATIONAL and ARCHIVAL purposes only.**  
> Running selfbots violates Discord's Terms of Service and can result in account termination.  
> The author assumes **NO RESPONSIBILITY** for any misuse, policy violations, or consequences.  
> **USE AT YOUR OWN RISK.**

---

## 📋 Overview

This selfbot combines various well known selfbot components, including reverse engineered code from *nighty* and other popular projects. Built with a focus on modularity and extensibility.

### Why This Project?
- **Community Driven**: Open to suggestions and contributions
- **Transparency**: All code is open source and reviewable

---

## ✨ Features

### Core Functionality
- ✅ **Advanced Message Management**
  - Snipe deleted/edited messages
  - Bulk delete with filters
  - Message logging and archiving
  - Auto-responder with custom triggers

- ✅ **User Enhancement**
  - Custom rich presence
  - Animated status rotation
  - Nitro features emulation
  - Token information display

- ✅ **Server Tools**
  - Mass DM capabilities
  - Server backup/clone
  - Member scraping
  - Role management automation

- ✅ **Utility Commands**
  - IP lookup and geolocation
  - Cryptocurrency prices
  - Weather information
  - Translation services

### GUI Features (In Development)
- 🚧 Modern dark themed interface
- 🚧 Real time console output
- 🚧 Configuration editor
- 🚧 Command palette
- 🚧 Statistics dashboard

### Security & Privacy
- 🔒 Encrypted token storage
- 🔒 Anti detection measures
- 🔒 Rate limit handling
- 🔒 Proxy support

---

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Git (for cloning the repository)
- Discord account token

### Quick Setup

1. **Download the Repository**
   ```bash
   idfk download tha bih
   cd SM SELFBOT SHI
   ```

2. **Install Dependencies**
   ```bash
   # Core dependencies
   pip install -r requirements.txt
   ```

3. **First Run Setup**
   ```bash
   # Initialize database and configs
   python setup.py
   ```

---

## 💻 Usage

### Starting the Bot
```bash
python main.py
```

### Basic Commands

| Command | Description | Example |
|---------|-------------|---------|  
| `.help` | Show all commands | `.help` |
| `.snipe` | Show last deleted message | `.snipe` |
| `.purge` | Delete messages | `.purge 50` |
| `.status` | Set custom status | `.status Playing a game` |
| `.backup` | Backup server | `.backup server_id` |
| `.userinfo` | Get user information | `.userinfo @user` |
| `.serverinfo` | Get server information | `.serverinfo` |
| `.ping` | Check bot latency | `.ping` |

### Advanced Usage

**Custom Commands**
```python
# Add to custom_commands.py
@selfbot.command()
async def mycommand(ctx, *, args):
    await ctx.send(f"Custom command: {args}")
```

**Auto Responder**
```json
// Add to config/autoresponder.json
{
  "triggers": [
    {
      "pattern": "hello",
      "response": "Hey there!",
      "exact_match": false
    }
  ]
}
```

---

## ⚙️ Configuration

### Environment Variables (.env)
```env
# Required
DISCORD_TOKEN=your_token_here
DISCORD_OWNER_ID=your_user_id

# Optional
PREFIX=.
DEBUG_MODE=false
LOG_LEVEL=INFO
USE_PROXY=false
PROXY_URL=http://proxy:port
```

### Config Files

**config/settings.json**
```json
{
  "prefix": ".",
  "delete_after": 5,
  "snipe_limit": 10,
  "auto_update": true,
  "rich_presence": {
    "enabled": true,
    "status": "online",
    "activity": "custom"
  }
}
```

**config/features.json**
```json
{
  "sniper": true,
  "autoresponder": false,
  "nitro_sniper": false,
  "giveaway_sniper": false,
  "anti_delete": true
}
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Ways to Contribute
- 🐛 Report bugs and issues
- 💡 Suggest new features
- 📝 Improve documentation
- 🔧 Submit pull requests
- ⭐ Star the repository

### Code Standards
- Follow PEP 8 style guide
- Add docstrings to functions
- Write tests for new features
- Update documentation

---

## 🐛 Troubleshooting

### Common Issues

**Token Invalid**
- Ensure your token is correct and not expired
- Check for extra spaces or quotes
- Verify the token has not been revoked

**Commands Not Working**
- Check prefix in settings
- Verify cogs are loaded
- Check console for errors

**Rate Limited**
- Implement delays between actions
- Use proxy rotation
- Reduce request frequency

**GUI Not Starting**
- Install GUI dependencies: `pip install -r requirements-gui.txt`
- Check for display server (Linux)
- Update graphics drivers

### Getting Help
- Search [existing issues](https://github.com/0n4u/Modified-Discord-Selfbot/issues)
- Contact on Discord: **0.delay**

---

## 📚 Resources

### Documentation
- [Discord.py-self Docs](https://discordpy-self.readthedocs.io/)
- [Discord.py Docs](https://discordpy.readthedocs.io/)
- [Discord API Docs](https://discord.com/developers/docs/intro)
- [Python Async Guide](https://docs.python.org/3/library/asyncio.html)

### Related Projects
- Various selfbot repositories (educational reference)
- Discord API libraries
- Bot development tools

---

## 🗺️ Roadmap

### Current Focus
- ✅ Core selfbot functionality
- ✅ Basic command system
- 🚧 GUI implementation (Still working on)
- 🚧 Anti-detection measures (Still working on)

### Future Plans 
- ⏳ Advanced automation features
- ⏳ AI-powered responses
- ⏳ Advanced scripting engine
- ⏳ Multi-account support
- ⏳ Cloud synchronization

---

### Acknowledgments
- Reverse-engineered components from various projects
- Community contributors and testers
- Open source Discord libraries
- *nighty* and other inspirations

---

<div align="center">

### ⭐ If you find this educational, please star the repository! ⭐

**Remember: Use responsibly and for educational purposes only**

*"chaos needs structure"*

[![Discord](https://img.shields.io/badge/Contact-0.delay-7289DA?logo=discord&logoColor=white)]()

</div>
