<div align="center">
  <img src="https://img.shields.io/badge/fastfetch-2.64%2B-89b4fa?style=flat-square" alt="fastfetch"/>
  <img src="https://img.shields.io/badge/theme-Catppuccin%20Mocha-cba6f7?style=flat-square" alt="theme"/>
  <img src="https://img.shields.io/badge/platform-Windows%20|%20Linux-94e2d5?style=flat-square" alt="platform"/>
</div>

# 🐱 fastfetch-mocha

A **Catppuccin Mocha** themed [fastfetch](https://github.com/fastfetch-cli/fastfetch) configuration, crafted with care for both **Windows** and **Linux**.

> ✨ 由 [YuNaitang](https://github.com/YuNaitang) 制作并维护

---

## 📸 Preview

### Windows
```
󰌢  System   master@BADAPPLE
󰌢  OS ﹄ Windows 11 专业版 Insider Preview (25H2) x86_64
  Host ﹄ OMEN by HP Gaming Laptop 16-wf0xxx
  Kernel ﹄ WIN32_NT 10.0.26220.8575
󰏗  Packages ﹄ 5 (choco), 9 (scoop)
󰍛  CPU ﹄ 13th Gen Intel(R) Core(TM) i5-13500HX (20) @ 2.69 GHz
󰑭  Memory ﹄ [ ■■■■■■■■■------ ] 18.34 GiB / 31.70 GiB (57.8%)
󰋊  Disk (OS)C:\ ﹄ [ ■■■■■■■■------- ] 247.53 GiB / 474.39 GiB (52.2%)
󰈀  LAN ﹄ 198.18.0.1/30
󰸗  Time ﹄ 2026-06-17 20:58:16
󰖟  Quote ﹄ 苦难不是结果，而是过程。
```

> **Note:** ASCII logo not displayed in preview above.

## 🚀 Usage

### Windows

1. **Install [fastfetch](https://github.com/fastfetch-cli/fastfetch)**

   ```powershell
   winget install fastfetch
   # or
   scoop install fastfetch
   ```

2. **Clone or copy config**

   ```powershell
   git clone https://github.com/YuNaitang/fastfetch-mocha.git
   # Copy to fastfetch config directory
   mkdir -Force ~\.config\fastfetch
   copy .\windows\* ~\.config\fastfetch\
   ```

3. **Run**

   ```powershell
   fastfetch
   ```

### Linux

_Coming soon — Linux config in the `linux/` directory._

## 📁 Directory Structure

```
fastfetch-mocha/
├── windows/          # Windows configuration
│   ├── config.jsonc  # Main config (JSON with comments)
│   └── logo          # ASCII art logo
├── linux/            # Linux configuration (WIP)
├── LICENSE           # MIT License
└── README.md         # This file
```

## 🎨 Theme Colors (Catppuccin Mocha)

| Role      | Color  | Hex       |
|-----------|--------|-----------|
| Mauve     | Title  | `#cba6f7` |
| Teal      | OS     | `#89dceb` |
| Blue      | Kernel | `#89b4fa` |
| Yellow    | Uptime | `#f9e2af` |
| Green     | Pkg    | `#a6e3a1` |
| Peach     | CPU    | `#fab387` |
| Maroon    | GPU    | `#f9e2af` |
| Pink      | DE     | `#f5c2e7` |
| Red       | Font   | `#f2cdcd` |
| Lavender  | WM     | `#b4befe` |
| Subtext1  | Output | `#cdd6f4` |

## 📋 Features

- **Catppuccin Mocha** color scheme throughout
- **Custom ASCII logo** with mauve accent
- **Progress bars** for CPU, memory, disk usage
- **Multi-NIC display** — physical, virtual, VPN all shown
- **One-liner quote** from [Hitokoto](https://hitokoto.cn/) with local cache fallback
- **Nerd Font icons** for visual clarity

## ⚙️ Requirements

- [fastfetch](https://github.com/fastfetch-cli/fastfetch) 2.64+
- A [Nerd Font](https://www.nerdfonts.com/) (e.g., JetBrainsMono Nerd Font)
- Windows 10/11 (for Windows config)
- `curl.exe` (built-in on Windows 10+)

## 📄 License

MIT © [YuNaitang](https://github.com/YuNaitang)
