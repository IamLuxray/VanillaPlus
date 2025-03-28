---

# **Vanilla+ Minecraft 1.21.4 (Fabric) – Modpack**  

💎 **Více než 370 modů** zaměřených pouze na **vizuální stránku a QoL vylepšení**, přičemž zachovávají **Vanilla gameplay a feel**.  

---

## 📌 **Prerekvizity**  

### ☕ **Java JDK 22+**  
1. Otevři **CMD** a napiš:  
   ```sh
   java -version
   ```
   Stiskni **Enter**.  
2. Pokud se zobrazí verze **nižší než 22**, pokračuj dalším krokem. Pokud vidíš **22 nebo vyšší** (screenshot), přeskoč na **Instalaci**.
 <img src="https://github.com/IamLuxray/VanillaPlus/blob/main/screen1.PNG?raw=true" alt="Správně">
3. Otevři:  
   ```
   Start -> Upravit proměnné prostředí systému  
   ```
   - V **záložce Upřesnit** klikni na **Proměnné prostředí...**  
   - Ve spodním okně najdi řádek začínající **Path** → Klikni na **Upravit...**  
   - Najdi **jakoukoliv zmínku o Java nebo Oracle** (většinou na disku, kde je Windows, např. C:).  
   - **Odstraň ji** → Klikni na **OK** → Zavři všechna okna.  
4. Stáhni a nainstaluj [**JDK 24**](https://download.oracle.com/java/24/latest/jdk-24_windows-x64_bin.exe).  
5. Po instalaci znovu spusť **CMD** a napiš:  
   ```sh
   java -version
   ```
   - Pokud **neuvidíš 24**, napiš mi na **Messenger** a fixneme to.  

---

## 🛠️ **Instalace**  

1. Stáhni celý **Archiv** (**Releases → Roaming.rar**) a extrahuj ho.  
2. Otevři:  
   ```sh
   Start -> %appdata% -> Enter
   ```
   - Nacházíš se ve složce **Roaming**.  
   - Pokud zde existuje složka **.minecraft**, **zálohuj ji** a poté **smaž**.  
3. Vlož do složky **Roaming** staženou složku **.minecraft**.  
4. Do stejné složky vlož i složku **sklauncher**.  
5. Ve složce **Roaming/sklauncher** si vytvoř zástupce **SKlauncher** a přesuň ho např. na **plochu**.  
6. ✅ **Hotovo!** Teď můžeš hrát **Minecraft** přes **SKlauncher**.  
   - V **SKlauncheru** se můžeš odhlásit a přihlásit se svým **(warez) jménem**.  

---

## ⚠️ **Pokud máš jiný disk než C:**  

Pokud máš systémový disk **D: / E: / apod.**, proveď navíc tento krok:  

1. Klikni **pravým tlačítkem** na zástupce **SKlauncher** (na ploše nebo v **%appdata%\Roaming\sklauncher**).  
2. Otevři **Vlastnosti** → Přepni na záložku **Zástupce**.  
3. Uprav řádek **Cíl** tak, aby obsahoval správné písmeno disku:  
   ```sh
   [DISK]:\Users\[UZIVATEL]\AppData\Roaming\sklauncher\jre\bin\javaw.exe -Xmx512M -jar "[DISK]:\Users\[UZIVATEL]\AppData\Roaming\sklauncher\SKlauncher.jar"
   ```
   Například pro **E:**  
   ```sh
   E:\Users\Skibidi\AppData\Roaming\sklauncher\jre\bin\javaw.exe -Xmx512M -jar "E:\Users\Skibidi\AppData\Roaming\sklauncher\SKlauncher.jar"
   ```
   - **Nezapomeň na dvojtečku a uvozovky!**  

---

## 🎮 **Zlepšení výkonu**  

- Pokud hra běží stabilně, zapni **Solas Shadery** pro lepší vizuál.  
- Udrží **60 FPS** i na starších sestavách:  
  - **GPU:** NVidia GeForce GTX 1060 (6GB GDDR5)  
  - **CPU:** Ryzen 5 1600X (6 jader, 3,6 GHz)  
  - **RAM:** DDR4 32GB (2666 MHz)  
- Pokud máš **RTX GPU**, použij shadery **Rethinking Voxels** s **low-performance ray tracingem**.  

---

## 📷 **Gameplay screenshoty (4K, Solas Shaders)**  

![Screenshot 1](2025-03-27_21.57.29_4K.png?raw=true)  
![Screenshot 2](2025-03-27_22.49.37_4K.png?raw=true)  
![Screenshot 3](2025-03-27_22.48.08_4K.png?raw=true)  
![Screenshot 4](2025-03-27_23.18.06_4K.png?raw=true)  
![Screenshot 5](2025-03-27_23.19.32_4K.png?raw=true)  

---

## ❗ **Známé problémy**  

- **První spawn** je **ve velké výšce**, což může znamenat **pádovou smrt**. Další respawny už jsou v pohodě.  
- **Distant Horizons mod** (větší vykreslovaná vzdálenost) **někdy přestane renderovat chunky** po změně nastavení.  
  - **Fix:** Restartuj svět nebo hru.  
- **Některé keybindy se kryjí**, ale to si můžeš snadno upravit.  

---

## 📜 **Seznam modů (výběr)**  

```sh
accessories-fabric-1.2.19-beta+1.21.4.jar
actuallyharvest-1.21.4-1.1.2.1-FABRIC.jar
additionallanterns-1.1.1-fabric-mc1.21.4.jar
AdditionalStructures-1.21.x-(v.5.0.1-fabric).jar
adorabuild-structures-2.9.1-fabric-1.21.4.jar
advancednetherite-fabric-2.2.2-1.21.4.jar
AdvancementPlaques-1.21.4-fabric-1.6.9.jar
Almanac-1.21.3-fabric-1.4.4.jar
AmbientSounds_FABRIC_v6.1.3_mc1.21.4.jar
animal_feeding_trough-1.1.3+1.21.4.jar
appleskin-fabric-mc1.21.3-3.0.6.jar
architectury-15.0.3-fabric.jar
areas-1.21.4-6.1.jar
armored-elytra-1.4.1.jar
ArmorStatues-v21.4.0-1.21.4-Fabric.jar
ArmorTrimItemFix-fabric-1.21.4-2.0.0.jar
audio_engine_tweaks-1.2.6-MC1.21.1 build 22.jar
axolotlbuckets-1.4.1+1.21.4.jar
BadOptimizations-2.2.1-1.21.2-21.4.jar
badpackets-fabric-0.8.2.jar
balm-fabric-1.21.4-21.4.22.jar
Bedrodium-0.3.0.jar
better-babies-0.7.17.jar
better-lush-caves-1.3.3.jar
...
```
📁 _(Kompletní seznam je dostupný ve složce modpacku.)_  

---

📩 **Pokud máš jakékoliv problémy, napiš mi!** 🚀  

Tady máš README vylepšené pro lepší čitelnost, s čistým GitHub markdownem a ikonami pro rychlou orientaci. Pokud chceš další úpravy, dej vědět! 🚀
