# <img src='images/icon.png' width='40' align='left'/> Rex Lapis Theme 🌋

**FAN-MADE, NOT OFFICIAL, Geo Archon Theme for VS Code**  
*\"In code as in contracts, elegance must be solid as stone.\" - Zhongli*

[![License: GPLv3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)

![Theme Preview](images/preview.png)  
*Palette: Liyue earth tones with amber and jade accents*

## 🌄 Key Features
- **Geossabic Palette**  
  Colors extracted from Zhongli's attire:
  - `#2D241C` Basalt Stone
  - `#B88B4A` Liyue Amber
  - `#5C7C9C` Night Sky
  - `#E3C17B` Meteor Glow

- **Optimized for**:
  ```txt
  JavaScript/TypeScript • Python • C# • HTML/CSS • JSON
  Markdown • Rust • Java • PHP • Shell Script
  ```

- **Special Elements**:
  - 🏮 Liyue-themed icons
  - 🗿 Layered stone bracket highlighting

## 🛠 Installation
### Via Marketplace (NOT AVALIABLE YET)
1. Open **VS Code**
2. `Ctrl+P` → `ext install Rex Lapis Theme`
3. Select theme in settings:
   ```json
   "workbench.colorTheme": "Rex Lapis"
   ```

### Manual (.vsix file)
```powershell
code --install-extension rex-lapis-theme-1.0.0.vsix
```

## 🎨 Customization
Add to `settings.json` for adjustments:
```json
{
  "workbench.colorCustomizations": {
    "[Rex Lapis]": {
      "statusBar.background": "#1A2A3A",
      "editor.selectionBackground": "#B88B4A55"
    }
  },
  "editor.tokenColorCustomizations": {
    "[Rex Lapis]": {
      "comments": "#63594D",
      "functions": "#FFD700"
    }
  }
}
```

## 🏗 Development
1. Clone repository:
   ```bash
   git clone https://github.com/your-username/rex-lapis-theme.git
   ```
2. Install dependencies:
   ```bash
   npm install -g @vscode/vsce
   ```
3. Package:
   ```bash
   vsce package --no-dependencies
   ```

## 🤝 Contributing
We accept:
- 🌌 New geo design elements
- 🖋 Token translations
- 🐞 Bug reports
- 📚 Documentation improvements

Submit PRs to our [GitHub Repository](https://github.com/vwinck-dev/vscode-zhongli-theme)

## 📜 License
GNU GPLv3 © 2024 Vwinck - See [LICENSE](LICENSE) for details