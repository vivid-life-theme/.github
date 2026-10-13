<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vivid-life-theme/vivid-life-design-system/main/assets/wordmark-dark.svg" />
    <img src="https://raw.githubusercontent.com/vivid-life-theme/vivid-life-design-system/main/assets/wordmark.svg" height="48" alt="Vivid Life Theme" />
  </picture>
</p>

<p align="center">
  A multi-flavor color scheme system &nbsp;·&nbsp; 4 flavors × 6 variants = 24 themes &nbsp;·&nbsp; WCAG AA verified
</p>

<p align="center">
  <img src="https://img.shields.io/badge/WCAG-AA%20%E2%9C%93-22c55e" alt="WCAG AA" />
  <img src="https://img.shields.io/badge/license-MIT-3b82f6" alt="License: MIT" />
  <img src="https://img.shields.io/npm/v/%40vivid-life-theme%2Fdesign-system?color=a855f7&label=npm" alt="npm" />
  <img src="https://img.shields.io/badge/dependencies-none-737373" alt="No dependencies" />
</p>

<br />

<p align="center">
  <img
    src="https://raw.githubusercontent.com/vivid-life-theme/vivid-life-design-system/main/assets/accent-grid.svg"
    alt="4 flavors × 6 variants = 24 themes · all WCAG AA"
  />
</p>

<table align="center">
  <tr>
    <td align="center">
      <img
        src="https://raw.githubusercontent.com/vivid-life-theme/vivid-life-design-system/main/assets/screenshots/kitchen-sink-midnight.png"
        width="180"
        alt="Midnight"
      /><br /><sub>Midnight</sub>
    </td>
    <td align="center">
      <img
        src="https://raw.githubusercontent.com/vivid-life-theme/vivid-life-design-system/main/assets/screenshots/kitchen-sink-twilight.png"
        width="180"
        alt="Twilight"
      /><br /><sub>Twilight</sub>
    </td>
    <td align="center">
      <img
        src="https://raw.githubusercontent.com/vivid-life-theme/vivid-life-design-system/main/assets/screenshots/kitchen-sink-dawn.png"
        width="180"
        alt="Dawn"
      /><br /><sub>Dawn</sub>
    </td>
    <td align="center">
      <img
        src="https://raw.githubusercontent.com/vivid-life-theme/vivid-life-design-system/main/assets/screenshots/kitchen-sink-noon.png"
        width="180"
        alt="Noon"
      /><br /><sub>Noon</sub>
    </td>
  </tr>
</table>

---

24 themes, one source of truth, zero eye strain. Every port below is generated from the same design tokens and gated for WCAG AA contrast, so switching from your editor to your terminal to your prompt doesn't feel like walking into a different building. Pick a flavor by time of day (Midnight, Twilight, Dawn, Noon), pick an accent, done. Bikeshedding over your color scheme has officially been automated.

---

### 🟢 Foundation

**[vivid-life-design-system](https://github.com/vivid-life-theme/vivid-life-design-system)** — Token source of truth · CSS custom properties · ES module · No dependencies

```bash
npm install @vivid-life-theme/design-system
```

---

### 🟢 Terminals

**[vivid-life-windows-terminal](https://github.com/vivid-life-theme/vivid-life-windows-terminal)** — Windows Terminal color scheme · 24 themes · installs as a JSON Fragment Extension, no `settings.json` surgery

```powershell
git clone https://github.com/vivid-life-theme/vivid-life-windows-terminal.git
cd vivid-life-windows-terminal
.\install.ps1
```

**[vivid-life-xfce4-terminal](https://github.com/vivid-life-theme/vivid-life-xfce4-terminal)** — Xfce Terminal color scheme · 24 themes

```bash
git clone https://github.com/vivid-life-theme/vivid-life-xfce4-terminal.git
cd vivid-life-xfce4-terminal
./install.sh
```

---

### 🟢 Shells & prompts

**[vivid-life-fish](https://github.com/vivid-life-theme/vivid-life-fish)** — fish shell color theme · 24 themes · Fisher-installable

```fish
fisher install vivid-life-theme/vivid-life-fish
```

**[vivid-life-powershell](https://github.com/vivid-life-theme/vivid-life-powershell)** — PowerShell color theme (PSReadLine + `$PSStyle`) · 24 themes · PowerShell Gallery

```powershell
Install-Module -Name VividLifePowerShell -Scope CurrentUser
```

**[vivid-life-starship](https://github.com/vivid-life-theme/vivid-life-starship)** — Starship cross-shell prompt theme · 24 themes, each with a colors-only and a custom-prompt config

```bash
git clone https://github.com/vivid-life-theme/vivid-life-starship.git
mkdir -p ~/.config
cp vivid-life-starship/themes/vivid-life-midnight-purple.toml ~/.config/starship.toml
```

---

### 🟢 Editors & tools

**[vivid-life-vs-code](https://github.com/vivid-life-theme/vivid-life-vs-code)** — VS Code color theme · 24 themes · VS Code Marketplace

```bash
code --install-extension vivid-life-theme.vivid-life-theme
```

**[vivid-life-claude-code](https://github.com/vivid-life-theme/vivid-life-claude-code)** — Claude Code color theme · 24 themes · Claude Code plugin

```text
/plugin marketplace add vivid-life-theme/vivid-life-claude-code
/plugin install vivid-life-theme@vivid-life
```

---

### 🟡 Desktop _(pre-release)_

**[vivid-life-xfce](https://github.com/vivid-life-theme/vivid-life-xfce)** — Xfce desktop theme (GTK2 · GTK3 · GTK4 · Xfwm4) · 24 themes · auto-detecting installer

```bash
git clone https://github.com/vivid-life-theme/vivid-life-xfce.git
cd vivid-life-xfce
./install.sh
```

---

### ⚪ Coming soon

| Repo                 | Description                                                 |
| -------------------- | ----------------------------------------------------------- |
| `vivid-life-neovim`  | Neovim color scheme (the modal-editor flame war comes free) |
| `vivid-life-windows` | Windows 11 accent theme                                     |

---

<p align="center">
  Building a new port with Claude Code? Read the <a href="https://github.com/vivid-life-theme/vivid-life-design-system/blob/main/handoff/README.md">handoff guide →</a>
</p>
