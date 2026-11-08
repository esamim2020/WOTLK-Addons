# GGRaid - World of Warcraft 3.3.5a LFM & Spam Addon

**GGRaid** is a lightweight and powerful World of Warcraft addon designed specifically for 3.3.5a private servers. It automates your Looking For More (LFM) raid recruitment by generating structured messages and automatically broadcasting them via Yell (`/yell`) and custom channels (like Global) at custom intervals.

---

## ✨ Features

- **Advanced LFM Builder UI:** Easily select your Raid (ICC, RS, TOC, VOA), size (10/25), difficulty (Normal/HC), and needed class talents or roles (Tanks, Healers, MDPS, RDPS) with a single click.
- **Auto Yell & Channel Broadcasting:** Set custom intervals for automated Yelling and channel spamming.
- **Macro Achievement Integration:** Seamlessly bypasses 3.3.5 client restrictions by reading achievement links directly from a designated macro (`GGRaidAch`).
- **Pure Custom Spam Mode:** Toggle to an override mode to broadcast any custom text you want.
- **Lightweight & Clean UI:** Styled with Blizzard standard color codes, dark custom input boxes, and an intuitive control panel.

---

## 📥 Installation

1. Download or clone this repository.
2. Rename the folder to **`GGRaid`** (make sure the TOC file matches the folder name).
3. Move the `GGRaid` folder into your World of Warcraft directory:
   `World of Warcraft\Interface\AddOns\`
4. Launch the game and enable load out of outdated addons if prompted.

---

## 🎮 How to Use & Commands

Available Slash Commands:
/ggraidui — Toggles the main controller UI.

/ggraid startyell — Starts automated Yell broadcasting.

/ggraid stopyell — Stops automated Yell.

/ggraid startchan — Starts automated channel broadcasting.

/ggraid stopchan — Stops channel broadcasting.

/ggraid channel Global — Sets and joins your advertising channel (e.g., Global).

/ggraid ach — Pulls your linked achievement from the GGRaidAch macro.

/ggraid help — Displays the list of in-game commands.

💡 Setting up the Achievement Link (Important)
Due to 3.3.5a client security limitations regarding programmatic chat reading, achievement links are loaded via a macro:

Open your macro window in-game (/macro).

Create a new macro named exactly: GGRaidAch (case-sensitive).

Shift-Click your achievement into the macro body (e.g., The Light of Dawn or The Bane of the Fallen King).

Type /ggraid ach in chat to load it into the addon.

📝 License
This project is open-source and available under the MIT License.



Open the main addon control panel in-game using:
```text
/ggraidui
