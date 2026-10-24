# Blockwright

World tools for Minecraft: find seeds from a plain-language description, convert worlds between versions and editions, and make datapacks. It runs locally on your Mac in your browser.

**[Download the latest release →](https://github.com/sh1lll/blockwright/releases/latest)**

## What it does

- **Seed search.** Describe a world ("village near spawn, mansion within 1000 blocks, a river") and Blockwright searches real seeds. Supports Java 1.0–26.3 and Bedrock 1.18+.
- **Version Studio.** Compare one seed across versions, or recreate an old world's layout in a newer version.
- **World conversion.** Upgrade, downgrade, and convert Java ↔ Bedrock (Java ↔ Bedrock uses [Chunker](https://github.com/HiveGamesOSS/Chunker) and needs Java 21+). It always writes a new copy and never changes your original world.
- **Content Studio.** Make datapacks: recipes, mob drops, functions, advancements, tags.
- **Modpack check.** Scan a mods folder for conflicts and missing dependencies.
- **Extras.** Predict chest loot, ore positions and terrain height.
- **Any AI model, or none.** Works with Ollama, LM Studio, llama.cpp and other OpenAI-compatible endpoints. A built-in rule parser works with no model at all.

Results are checked against Mojang's official servers. The Compatibility tab shows that evidence.

## Install (macOS, Apple Silicon)

1. Download `blockwright-<version>-macos-arm64.zip` from [Releases](https://github.com/sh1lll/blockwright/releases) and unzip it.
2. Double-click **Blockwright**. Your browser opens at http://localhost:4177.
3. If macOS says the developer can't be verified, right-click Blockwright, choose **Open**, then **Open** again. You only need to do this once.

Blockwright keeps its files in `~/.blockwright`. Delete that folder to remove it completely.

## Feedback

Please report bugs and send feature requests in [Issues](https://github.com/sh1lll/blockwright/issues).

## Licence

Blockwright is free to use, and all rights are reserved. See [LICENSE](LICENSE). Open-source components are listed in [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

*Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.*
