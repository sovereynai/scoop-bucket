# Sovereyn Scoop Bucket

Official Scoop bucket for Sovereyn - the verifiable distributed intelligence network.

## Installation

```powershell
scoop bucket add sovereyn https://github.com/sovereynai/scoop-bucket
scoop install reign
```

This will install both:
- **throne.exe** - The proprietary inference daemon
- **reign.exe** - The open-source CLI tool (MIT licensed)

## Quick Start

```powershell
# Start the throne daemon
throne serve

# Or use Windows Service (coming soon)
# sc create Sovereyn binPath="C:\path\to\throne.exe serve"

# Use the reign CLI
reign status
reign models
reign chat "Explain quantum computing"
```

## Prerequisites

Sovereyn requires Ollama for LLM models:

```powershell
# Install Ollama
scoop install ollama

# Pull a model
ollama pull llama3.2:3b

# Start Ollama
ollama serve
```

## Available Apps

- **reign** - Sovereyn throne daemon + reign CLI (v0.2.0)

## Links

- [Throne Repository](https://github.com/sovereynai/throne) - Proprietary daemon
- [Reign Repository](https://github.com/sovereynai/reign) - Open source CLI
- [Documentation](https://github.com/sovereynai/throne#readme)

## License

- Throne daemon: Proprietary
- Reign CLI: MIT License
- This bucket: MIT License

---

**Made with ❤️ by the Sovereyn community**

👑 Rule Your AI Destiny!
