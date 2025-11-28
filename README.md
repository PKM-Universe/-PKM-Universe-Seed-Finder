![GitHub Release](https://img.shields.io/github/v/release/PKM-Universe/-PKM-Universe-Seed-Finder)
![GitHub Downloads](https://img.shields.io/github/downloads/PKM-Universe/-PKM-Universe-Seed-Finder/total?color=violet)
![Build Status](https://img.shields.io/github/actions/workflow/status/PKM-Universe/-PKM-Universe-Seed-Finder/release.yml)

<p align="center">
  <img src="https://raw.githubusercontent.com/PKM-Universe/PKHeX-ALL-IN-ONE/main/banner.svg" alt="PKM-Universe Banner" width="600">
</p>

# PKM-Universe Seed Finder Plugins

Complete collection of **Seed Finder plugins** for PKHeX that generate **valid, legal Pokemon** by finding proper origin seeds.

## 🎮 Supported Games

| Plugin | Game | Description |
|--------|------|-------------|
| `PLZASeedFinderPlugin.dll` | Pokemon Legends Z-A | Find seeds with valid PID+ correlation |
| `SVSeedFinderPlugin.dll` | Pokemon Scarlet/Violet | Generate legal Tera Raid Pokemon |
| `SWSHSeedFinderPlugin.dll` | Pokemon Sword/Shield | Create specific Pokemon with valid seeds |

## 📥 Installation

1. Download the plugins from [Releases](https://github.com/PKM-Universe/-PKM-Universe-Seed-Finder/releases)
2. Place the `.dll` files in your PKHeX `plugins` folder
3. Restart PKHeX
4. Find the seed finders in the **Tools** menu

## ✨ Features

### All Plugins Include:
- **Valid Seed Generation** - Searches millions of seeds to find legal Pokemon
- **Proper Correlation** - Ensures PID, EC, IVs, nature all correlate correctly
- **Shiny Hunting** - Find specific shiny types (Square, Star, Never, Always)
- **IV Customization** - Set min/max for each stat
- **Nature Selection** - Target specific natures
- **Real-time Results** - See matches as they're found
- **CSV Export** - Save results for later use
- **Direct PKHeX Loading** - Double-click to load into editor

### PLZA Specific:
- Supports all encounter types (Wild, Static, Gift, Trade)
- Shiny Alpha support with PID+ correlation
- 64-bit seed range support

### SV Specific:
- Tera Raid seed finding
- Legal raid Pokemon generation

### SWSH Specific:
- Den seed finding
- Raid Pokemon generation

## 🔗 Links

- **PKM-Universe PKHeX**: [Download](https://github.com/PKM-Universe/PKHeX-ALL-IN-ONE/releases)
- **Discord**: [Join PKM-Universe](https://discord.gg/pkm-universe)
- **Ko-fi**: [Support Us](https://ko-fi.com/pokemonlover8888)

## 🛠️ Building from Source

```bash
git clone https://github.com/PKM-Universe/-PKM-Universe-Seed-Finder.git
cd -PKM-Universe-Seed-Finder
dotnet restore PKM-Universe-Seed-Finders.sln
dotnet build PKM-Universe-Seed-Finders.sln -c Release
```

The compiled DLLs will be in each plugin's `bin/Release/net9.0-windows/` folder.

## 📋 Requirements

- PKHeX (latest version recommended)
- Windows 10 or 11
- .NET 9.0 runtime

## 🙏 Credits

- **Kurt (@kwsch)** - For creating PKHeX
- **hexbyt3** - Original seed finder implementations
- **PKM-Universe Team** - Distribution and maintenance

## 📄 License

This project is licensed under the MIT License.

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/PKM-Universe">PKM-Universe</a>
</p>
