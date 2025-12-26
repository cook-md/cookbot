# Cookbot

AI-powered meal planning assistant using [Cooklang](https://cooklang.org/) format.

<img width="600" height="497" alt="cookbot" src="https://github.com/user-attachments/assets/bb503556-4fbf-49c1-8ef9-723a56f8e570" />

More info about [Cookbot](https://cook.md/help/cookbot).

## Installation

### macOS / Linux

```bash
curl -LsSf https://github.com/cook-md/cookbot/releases/latest/download/cookbot-installer.sh | sh
```


### Homebrew (macOS / Linux)

```bash
brew install cook-md/tap/cookbot
```

### Manual Download

Download the appropriate binary from the [releases page](https://github.com/cook-md/cookbot/releases).

## Usage

```bash
# Start cookbot in your recipes directory
cookbot ~/recipes

# Check for updates
cookbot --update

# Show help
cookbot --help
```

## Requirements

Cookbot requires a [cook.md](https://cook.md) account for AI features.

## Updates

Cookbot checks for updates on startup and prompts you to install if a new version is available. You can disable this with:

```bash
export COOKBOT_NO_UPDATE_CHECK=1
```

## License

MIT - See [LICENSE](LICENSE) for details.
