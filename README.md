# HRYNEHRAJEME – Neoficiální Linux / Batocera port (x86_64)

Komunitní linuxový balíček pro arkádové turnaje ve **WolfMAME** (určeno pro **Batocera Linux, SteamOS, Debian, Ubuntu** a další 64bitové Linux distribuce).

Projekt je postavený na původní oficiální desktopové utilitě **[HRYNEHRAJEME](https://github.com/hrynehrajeme/hrynehrajeme-upload-utility/releases)** a upravený pro bezproblémový chod na Linuxu a v prostředí Batocera Ports.

## 📦 Ke stažení
* **[Stáhnout HRYNEHRAJEME-2.7.9-Universal-Linux-Batocera.zip (129 MB)](https://github.com/snoopyk/HRYNEHRAJEME-Linux-Batocera/releases/download/v2.7.9/HRYNEHRAJEME-2.7.9-Universal-Linux-Batocera.zip)**

## 🚀 Rychlá instalace (Batocera Linux) "Testováno na ASUS ROG Xbox Ally X Z2 Extreme + Batocera v44"
1. Stáhni archiv `HRYNEHRAJEME-2.7.9-Universal-Linux-Batocera.zip` a rozbal ho v PC.
2. V souboru `ports/hrynehrajeme_official/config.json` vyplň své `username` a `password` z webu `hrynehrajeme.cz`.
3. Do složky `ports/hrynehrajeme_official/` nahraj svou Linux `x86_64` binárku WolfMAME (pojmenovanou jako `wolfmame`) a do podsložky `roms/` aktuální turnajové ROMky.
4. Zkopíruj celou složku `ports` na disk/SD kartu do `/userdata/roms/` (nebo přes síť `\\BATOCERA\share\roms\`).
5. Přes SSH nebo terminál (`F1` -> `Applications` -> `xterm`) nastav spustitelná práva:
   ```bash
   chmod +x /userdata/roms/ports/Hrynehrajeme.sh /userdata/roms/ports/hrynehrajeme_official/{HRYNEHRAJEME,run_wolfmame.sh,wolfmame}
   ```
6. V menu Batocery obnov seznam her (**Herní nastavení -> Aktualizovat seznamy her**) a spusť **Ports -> Hrynehrajeme**.

*(Podrobný návod i pro běžný desktopový Linux najdeš v souboru `README_LINUX_BATOCERA.txt` přímo uvnitř archivu.)*

---

# HRYNEHRAJEME – Unofficial Linux / Batocera Port (x86_64)

Community Linux package of the **HRYNEHRAJEME.cz** tournament client for **WolfMAME** arcade tournaments (designed for **Batocera Linux, SteamOS, Debian, Ubuntu**, and other 64-bit Linux distributions).

This project is based on the original official desktop utility **[HRYNEHRAJEME](https://github.com/hrynehrajeme/hrynehrajeme-upload-utility/releases)** and adapted for smooth operation on Linux and Batocera Ports.

## 📦 Download
* **[Download HRYNEHRAJEME-2.7.9-Universal-Linux-Batocera.zip (129 MB)](https://github.com/snoopyk/HRYNEHRAJEME-Linux-Batocera/releases/download/v2.7.9/HRYNEHRAJEME-2.7.9-Universal-Linux-Batocera.zip)**

## 🚀 Quick Installation (Batocera Linux) "Tested on ASUS ROG Xbox Ally X Z2 Extreme + Batocera v44"
1. Download `HRYNEHRAJEME-2.7.9-Universal-Linux-Batocera.zip` and extract it on your PC.
2. Open `ports/hrynehrajeme_official/config.json` and fill in your `username` and `password` from `hrynehrajeme.cz`.
3. Place your Linux `x86_64` WolfMAME binary (named `wolfmame`) into `ports/hrynehrajeme_official/` and copy the current tournament ROMs into the `roms/` subfolder.
4. Copy the entire `ports` folder to `/userdata/roms/` on your drive/SD card (or via network share `\\BATOCERA\share\roms\`).
5. Set executable permissions via SSH or terminal (`F1` -> `Applications` -> `xterm`):
   ```bash
   chmod +x /userdata/roms/ports/Hrynehrajeme.sh /userdata/roms/ports/hrynehrajeme_official/{HRYNEHRAJEME,run_wolfmame.sh,wolfmame}
   ```
6. In Batocera, refresh your game list (**Game Settings -> Update Games Lists**) and launch **Ports -> Hrynehrajeme**.

*(Detailed instructions for standard desktop Linux distributions are included in `README_LINUX_BATOCERA.txt` inside the archive.)*
