# 💻 t480-dotfiles

Dotfiles & configuration repo for **ThinkPad T480**
Focused on **EndeavourOS (Arch Linux)** and **Hackintosh (config only)**.

> ⚠️ This repo stores **configs only** — no EFI, no serials, no SMBIOS, no sensitive data.

---

## 🧠 Device Info

| Item           | Value                    |
| -------------- | ------------------------ |
| Model          | Lenovo ThinkPad T480     |
| Product Name   | 20L50011US               |
| CPU            | Intel Core i5-8350U      |
| RAM            | 32 GB                    |
| GPU            | Intel UHD Graphics 620   |
| OS             | EndeavourOS / Hackintosh |
| Display Server | Wayland                  |
| Desktop        | KDE Plasma               |

---

## 🗂 Repository Structure

```txt
t480-dotfiles/
├── bin/                  # personal scripts & helpers
├── config/
│   ├── linux/            # EndeavourOS / Arch configs
│   │   ├── kde/
│   │   ├── hyprland/
│   │   ├── waybar/
│   │   ├── kitty/
│   │   ├── zsh/
│   │   └── system/
│   │
│   ├── hackintosh/       # macOS / Hackintosh configs (NO EFI)
│   │   ├── opencore/     # config.plist & OC-related settings
│   │   ├── power/        # power management tuning
│   │   ├── usb-map/      # USB map configs
│   │   └── notes/        # tuning notes & docs
│   │
│   └── shared/           # cross-platform configs
│       ├── git/
│       ├── nvim/
│       └── vscode/
│
├── icons/                # custom icons
├── screenshots/          # desktop previews (optional)
├── LICENSE
└── README.md
```

---

## 🐧 Linux Setup (EndeavourOS)

Contains configs for:

* KDE Plasma
* Zsh
* System tweaks

---

## 🍏 Hackintosh Scope

This repo includes:

* `config.plist` (sanitized)
* OpenCore tuning
* USB map config
* Power management notes

❌ Not included:

* EFI folder
* Serial / MLB / ROM
* Kext binaries
* Any sensitive hardware identifiers

---

## 🚀 Usage

Clone repo:

```bash
git clone https://github.com/<username>/t480-dotfiles.git
cd t480-dotfiles
```

Symlink configs manually or using tools like:

* `stow`
* `chezmoi`
* custom script in `bin/`

---

## 🧩 TODO / Roadmap

* [ ] Symlink installer script
* [ ] Package list backup (Arch)
* [ ] Hackintosh tuning checklist
* [ ] Screenshots & desktop preview
* [ ] Automation bootstrap script

---

## 📸 Preview (Optional)

Screenshots can be placed in `screenshots/`.

---

## 🧠 Notes

This repo is tailored for:

* ThinkPad T480
* Power-efficient tuning
* Clean & reproducible dotfiles
* Cross-OS config workflow

---

## 📜 License

MIT — feel free to fork & adapt.
