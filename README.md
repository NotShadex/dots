***

# 🌿 Rosé Pine KDE Plasma Dots

Personal KDE Plasma configuration files featuring a full Rosé Pine theme setup

---

## 🎨 Why this exists?
> "I forget how to make KDE look clean."

---

## 📂 Repository Structure
The folder structure mimics the Linux filesystem for easy setup:

*   **`.local/share/`**: Contains global color schemes, icon packs, and fonts.
*   **`.icons/`**: Contains the cursor packs.
*   **`.config/`**: (If applicable) configuration files for Starship, Kitty, and more.

---

## 🚀 Installation & Setup

### 1. File Placement
Move the folders to their respective locations in your home directory:
- Extract fonts and icons into `~/.local/share/`
- Extract cursors into `~/.icons/`

### 2. Terminal Setup (Starship)
To get the Starship prompt working add the following line to the end of your `~/.bashrc`:

```bash
eval "$(starship init bash)"
```

### 3. Window Rules 
1. Go to **System Settings** > **Window Management** > **Window Rules**.
2. Click **Add New...**
3. Set **Window class** to: `Unimportant`.
4. Set **Window types** to: `All Selected`.
5. Click **Add Property** > Search **Active opacity** and **Inactive opacity**.
6. Set both to **90%** and select **Force**.

### 4. Polishing the UI
*   **Application Style:** Keep at **Breeze**.
*   **Window Decorations:** Keep at **Breeze**.
*   **Launch Feedback:** To disable the annoying bouncing icon:
    *   Go to **Settings** > **Colors & Themes** > **Cursors**.
    *   Click **Configure Launch Feedback** and set it to **No Feedback** or **Static**.

---

## 🧩 Extensions
Found at Top Panel > Show Panel configuration:

*   🖼️ **Wallpaper Effects** – Enhanced background transitions.
*   🚀 **Andromeda Launcher** – A clean, modern application launcher.
*   🎵 **Plasmusic Toolbar** – Media controls directly in your panel.
*   🏷️ **Window Title** – Displays the active window name in the panel.
*   🖥️ **Desktop Indicator** – Minimalist workspace switcher.
*   🎨 **Panel Colorizer** – Deep customization for panel transparency and color.
*   ⚙️ **KDE Control Station** – A mobile-style toggles menu for Wi-Fi, BT, and Brightness.

---

## 🔗 Resources & Credits
The latest versions of the themes used in this setup:

| Component | Source Link |
| :--- | :--- |
| **Starship Theme** | [GitHub - Rosé Pine Starship](https://github.com/rose-pine/starship) |
| **KDE Color Scheme** | [GitHub - Ashbork KDE](https://github.com/ashbork/kde) |
| **Terminal (Kitty)** | [GitHub - Rosé Pine Kitty](https://github.com/rose-pine/kitty) |
| **Icons** | [Yet Another Monochrome Icon Set](https://store.kde.org/p/2303161) |
| **Firefox** | [GitHub - Rosé Pine Firefox](https://github.com/rose-pine/firefox) |
| **Fonts** | [Roboto](https://fonts.google.com/specimen/Roboto) & [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) |
| **Main Theme** | [Rosé Pine Official](https://rosepinetheme.com/themes/) |

---

## 🛠️ Work in Progress

- [ ] Finish **Neovim** (NVIM) configuration.

