# HRYNEHRAJEME – Neoficiální Linux / Batocera port (x86_64)

Komunitní linuxový balíček oficiálního klienta **HRYNEHRAJEME.cz** pro arkádové turnaje ve **WolfMAME** (určeno pro **Batocera Linux, SteamOS, Debian, Ubuntu** a další 64bitové Linux distribuce).

## 📦 Ke stažení (Releases)
Aktuální instalační balíček najdeš vpravo v sekci **[Releases](../../releases)**:
* **`HRYNEHRAJEME-2.7.9-Universal-Linux-Batocera.zip`** – kompletní balíček pro **Batocera / Linux (x86_64)**

## 🚀 Rychlá instalace (Batocera Linux)
1. Stáhni archiv `HRYNEHRAJEME-2.7.9-Universal-Linux-Batocera.zip` ze sekce **Releases** a rozbal ho v PC.
2. V souboru `ports/hrynehrajeme_official/config.json` vyplň své `username` a `password` z webu `hrynehrajeme.cz`.
3. Do složky `ports/hrynehrajeme_official/` nahraj svou Linux `x86_64` binárku WolfMAME (pojmenovanou jako `wolfmame`) a do podsložky `roms/` aktuální turnajové ROMky.
4. Zkopíruj celou složku `ports` na disk/SD kartu do `/userdata/roms/` (nebo přes síť `\\BATOCERA\share\roms\`).
5. Přes SSH nebo terminál (`F1` -> `Applications` -> `xterm`) nastav spustitelná práva:
   ```bash
   chmod +x /userdata/roms/ports/Hrynehrajeme.sh /userdata/roms/ports/hrynehrajeme_official/{HRYNEHRAJEME,run_wolfmame.sh,wolfmame}
   ```
6. V menu Batocery obnov seznam her (**Herní nastavení -> Aktualizovat seznamy her**) a spusť **Ports -> Hrynehrajeme**.

*(Podrobný návod i pro běžný desktopový Linux najdeš v souboru `README_LINUX_BATOCERA.txt` přímo uvnitř archivu.)*
