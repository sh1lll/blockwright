# Blockwright

World tools for Minecraft: find seeds from a plain-language description, convert worlds between versions and editions, and make datapacks. It runs on your own computer (macOS, Windows or Linux) and you use it in your browser.

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

## Install

Download the file for your computer from the [latest release](https://github.com/sh1lll/blockwright/releases/latest):

| Computer | File |
|---|---|
| Mac with Apple Silicon (M1 or newer) | `blockwright-<version>-macos-arm64.zip` |
| Mac with Intel | `blockwright-<version>-macos-x64.zip` |
| Windows 10/11 (64-bit) | `blockwright-<version>-windows-x64.zip` |
| Linux (64-bit) | `blockwright-<version>-linux-x64.tar.gz` |

Unzip it and open **Blockwright**. Your browser opens at http://localhost:4177.

- **macOS:** if it says the developer can't be verified, right-click Blockwright, choose **Open**, then **Open** again. You only need to do this once.
- **Windows:** if SmartScreen says it protected your PC, click **More info**, then **Run anyway**. You only need to do this once.
- **Linux:** run `./Blockwright` from a terminal.

Converting worlds between Java and Bedrock needs [Java 21 or newer](https://adoptium.net).

Blockwright keeps its files in a `.blockwright` folder in your home folder. Delete that folder to remove it completely.

## Feedback

Please report bugs and send feature requests in [Issues](https://github.com/sh1lll/blockwright/issues).

## Licence

Blockwright is free to use, and all rights are reserved. See [LICENSE](LICENSE). Open-source components are listed in [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

*Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.*
