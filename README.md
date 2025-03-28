---

# **Vanilla+ Minecraft 1.21.4 (Fabric) – Modpack**  
### Stabilní **Release 2.1** je venku!

💎 **Více než 390 modů** zaměřených primárně na **vizuální stránku, QoL vylepšení a exploration**, přičemž zachovávají **Vanilla gameplay a feel**.  

---

## 📌 **Prerekvizity**  

### ☕ **Java JDK 22+**  
1. Otevři **CMD** a napiš:

   ```sh
   java -version
   ```
   Stiskni **Enter**.  
3. Pokud se zobrazí verze **nižší než 22**, pokračuj dalším krokem. Pokud vidíš **22 nebo vyšší** (screenshot), přeskoč na **Instalaci**.
 <img src="https://github.com/IamLuxray/VanillaPlus/blob/main/screen1.PNG?raw=true" alt="Správně">
4. Otevři:
   
   ```sh
   Start -> Upravit proměnné prostředí systému  
   ```
   
   - V **záložce Upřesnit** klikni na **Proměnné prostředí...**  
   - Ve spodním okně najdi řádek začínající **Path** → Klikni na **Upravit...**  
   - Najdi **jakoukoliv zmínku o Java nebo Oracle** (většinou na disku, kde je Windows, např. C:).  
   - **Odstraň ji** → Klikni na **OK** → Zavři všechna okna.  
6. Stáhni a nainstaluj **JDK 24**(https://download.oracle.com/java/24/latest/jdk-24_windows-x64_bin.exe).  
7. Po instalaci znovu spusť **CMD** a napiš:
   
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
- Nejlepší optimalizaci a performance mají **BSL shaders**, klidně i na High preset.
- Pokud máš **RTX GPU**, použij shadery **Rethinking Voxels** s **low-performance ray tracingem**.  

---

## 📷 **Gameplay screenshoty ve 4K (3x Solas Shaders High preset a 2x BSL shaders High preset)**  

![Screenshot 1](2025-03-27_21.57.29_4K.png?raw=true)  
![Screenshot 2](2025-03-27_22.49.37_4K.png?raw=true)  
![Screenshot 3](2025-03-27_22.48.08_4K.png?raw=true)  

---
![Screenshot 3](2025-03-28_18.58.48_4K.png?raw=true)  
![Screenshot 3](2025-03-28_19.01.48_4K.png?raw=true)  
   
---

## ❗ **Známé problémy**  

- **První spawn** je **ve velké výšce**, což může znamenat **smrt pádem z  výšky**. Další respawny už jsou ale v pohodě.  
- **Distant Horizons mod** (mod na větší vykreslovanou vzdálenost) **někdy přestane renderovat chunky** po změně jeho nastavení.  
  - **Fix:** Restartuj svět nebo hru.  
- **Některé keybindy se kryjí**, ale to si můžeš snadno upravit.  

---

## 📜 **Seznam modů**  

```sh
 accessories-fabric-1.2.19-beta+1.21.4.jar<br>
actuallyharvest-1.21.4-1.1.2.1-FABRIC.jar<br>
additionallanterns-1.1.1-fabric-mc1.21.4.jar<br>
AdditionalStructures-1.21.x-(v.5.0.1-fabric).jar<br>
adorabuild-structures-2.9.1-fabric-1.21.4.jar<br>
advancednetherite-fabric-2.2.2-1.21.4.jar<br>
AdvancementPlaques-1.21.4-fabric-1.6.9.jar<br>
Almanac-1.21.3-fabric-1.4.4.jar<br>
AmbientSounds_FABRIC_v6.1.3_mc1.21.4.jar<br>
animal_feeding_trough-1.1.3+1.21.4.jar<br>
appleskin-fabric-mc1.21.3-3.0.6.jar<br>
architectury-15.0.3-fabric.jar<br>
areas-1.21.4-6.1.jar<br>
armored-elytra-1.4.1.jar<br>
ArmorStatues-v21.4.0-1.21.4-Fabric.jar<br>
ArmorTrimItemFix-fabric-1.21.4-2.0.0.jar<br>
audio_engine_tweaks-1.2.6-MC1.21.1 build 22.jar<br>
axolotlbuckets-1.4.1+1.21.4.jar<br>
BadOptimizations-2.2.1-1.21.2-21.4.jar<br>
badpackets-fabric-0.8.2.jar<br>
balm-fabric-1.21.4-21.4.22.jar<br>
Bedrodium-0.3.0.jar<br>
better-babies-0.7.17.jar<br>
better-lush-caves-1.3.3.jar<br>
BetterAdvancements-Fabric-1.21.4-0.4.6.36.jar<br>
BetterAnimationsCollection-v21.4.0-1.21.4-Fabric.jar<br>
betterbeaconplacement-1.21.4-3.5.jar<br>
betterbeds-fabric-1.4.1.jar<br>
BetterGrassify-1.5.1+fabric.1.21.4.jar<br>
betterhurtcam-1.10.0+mc1.21.2.jar<br>
bettermounthud-1.2.5.jar<br>
bettersafebed-fabric-1.21.3-1.jar<br>
betterstats-3.13.9+fabric-1.21.4.jar<br>
BetterThanMending-2.2.3.jar<br>
bettervillage-fabric-1.21.4-3.3.0.jar<br>
biggerspongeabsorptionradius-1.21.4-3.7.jar<br>
bigger_end_cities-1.21.4-1.1.0.jar<br>
blooming-biospshere-v1.1.6.jar<br>
boatiview-fabric-0.0.6-1.21.4.jar<br>
bobby-5.2.6+mc1.21.4.jar<br>
boggedspawn-1.21.4-1.1.jar<br>
bottleyourxp-1.21.4-3.5.jar<br>
BowInfinityFix-1.21-fabric-3.1.0.jar<br>
breezespawn-1.21.4-1.1.jar<br>
brokenleadwarner-1.2.0+1.21.x.jar<br>
c2me-fabric-mc1.21.4-0.3.2+alpha.0.41.jar<br>
carryon-fabric-1.21.4-2.3.0.22.jar<br>
cavespiderspawn-1.21.4-1.2.jar<br>
chatanimation-1.0.6.jar<br>
chatnotify-fabric-2.4.2+1.21.4.jar<br>
chatsounds-1.1.11.jar<br>
chat_heads-0.13.14-fabric-1.21.4.jar<br>
Chunky-Fabric-1.4.27.jar<br>
cicada-lib-0.11.4+1.21.4-and-above.jar<br>
cinderscapes-5.2.0.jar<br>
cinderscapes-5.2.1-beta.1.jar<br>
CleanF3-mc1.20.x-0.4.9.jar<br>
clickthrough-plus-3.3+1.21.3.jar<br>
cloth-config-17.0.144-fabric.jar<br>
Clumps-fabric-1.21.4-22.0.0.1.jar<br>
cobweb-fabric-1.21.4-1.3.3.jar<br>
collective-1.21.4-7.94.jar<br>
conduitspreventdrowned-1.21.4-3.9.jar<br>
continuity-3.0.0+1.21.4.jar<br>
controlify-2.0.2+1.21.4-fabric.jar<br>
Corgilib-Fabric-1.21.4-6.0.0.0.jar<br>
coroutil-fabric-1.21.4-1.3.8.jar<br>
crash_assistant-fabric-1.4.3.jar<br>
CreativeCore_FABRIC_v2.12.35_mc1.21.4.jar<br>
cristellib-fabric-2.0.2.jar<br>
Crops-Love-Rain-2.4.1.jar<br>
cryingghasts-1.21.4-3.6.jar<br>
cullleaves-fabric-4.0.3.jar<br>
currentgamemusictrack-1.21.4-2.4.jar<br>
custom-lan-1.21.4-1.21.4-v2.3.2.jar<br>
customizableelytra-fabric-2.2.8+1.21.4.jar<br>
CustomSkinLoader_Fabric-14.23.jar<br>
CustomWindowTitle-1.21.4+v1.4.1.jar<br>
CutThrough-v21.4.0-1.21.4-Fabric.jar<br>
cwb-fabric-3.0.0+mc1.21.3.jar<br>
cyclepaintings-1.21.4-4.1.jar<br>
day-dream-1.0.14.jar<br>
Debugify-1.21.4+1.1.jar<br>
despawningeggshatch-1.21.4-4.5.jar<br>
DetailArmorBar-2.6.3+1.21.3-fabric.jar<br>
DiagonalFences-v21.4.0-1.21.4-Fabric.jar<br>
DiagonalWalls-v21.4.0-1.21.4-Fabric.jar<br>
Ding-1.21.4-Fabric-1.5.0.jar<br>
DisableAccessibilityScreen-1.1.0+1.21.4.jar<br>
DisableInsecureChatToast-mc1.20.6-1.1.0.jar<br>
DistantHorizons-neoforge-fabric-2.3.0-b-1.21.4.jar<br>
DistantHorizonsApi-4.0.0.jar<br>
DistinguishedPotions-v21.4.0-1.21.4-Fabric.jar<br>
doors-closed-1.0.0+1.19.4.jar<br>
doubledoors-1.21.4-6.2.jar<br>
do_a_barrel_roll-fabric-3.8.1+1.21.4.jar<br>
draggable_lists-mc1.21.4-1.0.10-build.49.jar<br>
drippyloadingscreen_fabric_3.0.11_MC_1.21.4.jar<br>
dungeons+-1.9.0b.jar<br>
dungeons-and-taverns-end-castle-standalone-v1.3.1.jar<br>
dungeons-and-taverns-nether-fortress-overhaul-v2.6.jar<br>
dungeons-and-taverns-swamp-hut-overhaul-v2.1.jar<br>
dungeons-and-taverns-v4.6.3.jar<br>
dungeons-and-taverns-woodland-mansion-replacement-v1.5.jar<br>
durabilitytooltip-1.1.5-fabric-mc1.21.jar<br>
dyed-fabric-1.21.4-1.2.0.jar<br>
dynamic-fps-3.9.1+minecraft-1.21.2-fabric.jar<br>
dynamiccrosshair-9.3+1.21.3-fabric.jar<br>
dynamiccrosshaircompat-4.0+1.21.3.jar<br>
e4mc_minecraft-fabric-5.3.0.jar<br>
EasyAnvils-v21.4.1-1.21.4-Fabric.jar<br>
easyelytratakeoff-1.21.4-4.5.jar<br>
EasyMagic-v21.4.1-1.21.4-Fabric.jar<br>
EasyShulkerBoxes-v21.4.2-1.21.4-Fabric.jar<br>
edibles-1.21.4-4.5.jar<br>
eg_particle_interactions-0.6.2-fabric-mc1.21.4.jar<br>
elytra_physics-fabric-2.2_mc1.21.2+.jar<br>
emotecraft-fabric-for-MC1.21.4-2.5.5.jar<br>
EnchantingInfuser-v21.4.0-1.21.4-Fabric.jar<br>
enchantment-lore-1.5.1+MC1.21.2-1.21.4.jar<br>
enchantmentlevelcapindicator-1.21.4-1.1.jar<br>
enchlevel-langpatch-2.2.8.jar<br>
EnderZoology-v21.4.0-1.21.4-Fabric.jar<br>
enhancedblockentities-0.11.3+1.21.4.jar<br>
entityculling-fabric-1.7.3-mc1.21.4.jar<br>
entity_model_features_fabric_1.21.4-2.4.1.jar<br>
entity_texture_features_fabric_1.21.4-6.2.10.jar<br>
EquipmentCompare-1.21.4-fabric-1.3.12.jar<br>
EuphoriaPatcher-1.5.2-r5.4-fabric.jar<br>
expanded-armor-enchanting-1.0.12.jar<br>
explorations-fabric-1.21.4-1.6.1.jar<br>
Explorify v1.6.2 f10-48.jar<br>
explosive-enhancement-1.3.0-1.21.4.jar<br>
fabric-api-0.118.5+1.21.4.jar<br>
fabric-language-kotlin-1.13.1+kotlin.2.1.10.jar<br>
fabrictailor-2.6.3.jar<br>
fabrishot-1.14.3.jar<br>
fallingleaves-1.17.0+1.21.4.jar<br>
FallingTree-1.21.4-1.21.4.7.jar<br>
FancyHealthBar-1.1.1-1.21.4.jar<br>
fancymenu_fabric_3.4.6_MC_1.21.4.jar<br>
fast-ip-ping-v1.0.5-mc1.21.1-fabric.jar<br>
fastconfigapi-2.1.0.jar<br>
fastitems-fabric-1.1.0-fabric+1.21.4.jar<br>
fastquit-3.0.0+1.21.4.jar<br>
fasttrading-0.2.2+1.21.4.jar<br>
Female-Gender-Mod-fabric-4.3.3+1.21.4.jar<br>
ferritecore-7.1.1-fabric.jar<br>
firstjoinmessage-1.21.4-3.7.jar<br>
firstperson-fabric-2.4.8-mc1.21.4.jar<br>
fishontheline-1.21.4-3.5.jar<br>
fluidvoidfading-1.2.0+1.21.4.jar<br>
followersteleporttoo-1.21.4-2.7.jar<br>
ForgeConfigAPIPort-v21.4.1-1.21.4-Fabric.jar<br>
forgivingvoid-fabric-1.21.4-21.4.3.jar<br>
furnacerecycle-1.21.4-2.6.jar<br>
fzzy_config-0.6.7+1.21.3.jar<br>
geckolib-fabric-1.21.4-4.8.4.jar<br>
getittogetherdrops-fabric-1.21-1.3.1.jar<br>
glassbreaker-2.0.0+1.21+fabric.jar<br>
GlitchCore-fabric-1.21.4-2.3.0.4.jar<br>
grassseeds-1.21.4-3.4.jar<br>
graves-3.6.0+1.21.4.jar<br>
grind-enchantments-4.0.1+1.21.4.jar<br>
hardcorerevival-fabric-1.21.4-21.4.4.jar<br>
head_in_the_clouds-1.3.0+1.21.4.jar<br>
healingcampfire-1.21.4-6.2.jar<br>
Highlighter-1.21.4-fabric-1.1.11.jar<br>
HopoBetterMineshaft-[1.21.4]-1.3.0.jar<br>
HopoBetterRuinedPortals-[1.21.4]-1.4.5.jar<br>
HopoBetterUnderwaterRuins-[1.21.4]-1.2.2.jar<br>
HorseBuff-1.21.4-2.2.1.jar<br>
HorseExpert-v21.4.1-1.21.4-Fabric.jar<br>
huskspawn-1.21.4-3.6.jar<br>
Iceberg-1.21.4-fabric-1.2.13.jar<br>
iChunUtil-1.21.4-Fabric-1.0.4.jar<br>
ImmediatelyFast-Fabric-1.3.6+1.21.4.jar<br>
ImmersiveUI-FABRIC-0.3.0+1.21.2.jar<br>
Incendium_1.21.x_v5.4.4.jar<br>
infinitetrading-1.21.4-4.6.jar<br>
InventorySorter-1.9.1-1.21.4.jar<br>
inventorytotem-1.21.4-3.4.jar<br>
iris-fabric-1.8.8+mc1.21.4.jar<br>
ItemBorders-1.21.4-fabric-1.2.5.jar<br>
ItemPhysicLite_FABRIC_v1.6.7_mc1.21.4.jar<br>
Jade-1.21.4-Fabric-17.2.2.jar<br>
jrftl-1.21.4-fabric-1.9.1.jar<br>
katters-structures-2.2.1.jar<br>
keepmysoiltilled-1.21.4-2.5.jar<br>
konkrete_fabric_1.9.9_MC_1.21.4.jar<br>
labellingcontainers-1.9.2.jar<br>
lambdynamiclights-4.0.2+1.21.4.jar<br>
language-reload-1.7.2+1.21.4.jar<br>
leash-villager-1.1-mc1.21.4.jar<br>
LeavesBeGone-v21.4.0-1.21.4-Fabric.jar<br>
LegendaryTooltips-1.21.4-fabric-1.5.1.jar<br>
letmedespawn-1.21.x-fabric-1.5.0.jar<br>
LetSleepingDogsLie-1.21.4-Fabric-1.3.0.jar<br>
libraryferret-fabric-1.21.4-4.0.0.jar<br>
lithium-fabric-0.15.0+mc1.21.4.jar<br>
lithostitched-fabric-1.21.4-1.4.5.jar<br>
livingthings-fabric-1.21.4-2.2.0.jar<br>
lootr-fabric-1.21.4-1.12.36.89.jar<br>
lost-libraries-1.1.2.jar<br>
MagnumTorch-v21.4.0-1.21.4-Fabric.jar<br>
main-menu-credits-1.2.0.jar<br>
make_bubbles_pop-0.3.1-fabric-mc1.21.2-1.21.4.jar<br>
Marlow's Crystal Optimizer-1.21.X-1.0.3.jar<br>
mastercutter-1.5-mc1.21.4.jar<br>
mavapi-fabric-1.2.1.jar<br>
mavm-fabric-1.3.1.jar<br>
mcw-paintings-1.0.5-1.21.4fabric.jar<br>
melody_fabric_1.0.10_MC_1.21.jar<br>
mes-1.4.2-1.21.4.jar<br>
milkallthemobs-1.21.4-3.4.jar<br>
mine-spawners-1.5.1.jar<br>
mixintrace-1.1.1+1.17.jar<br>
mns-1.1.2-1.21.4.jar<br>
modelfix-1.21.3-1.10-fabric.jar<br>
modernfix-fabric-5.20.3+mc1.21.4.jar<br>
modmenu-13.0.3.jar<br>
modmenu-badges-lib-2023.6.1.jar<br>
mooshroomtweaks-1.21.4-3.6.jar<br>
MoreArmorStandVariants-1.3.0+1.21.4-Fabric.jar<br>
MoreBarrelVariants-1.7.7+1.21.4-Fabric.jar<br>
MoreBedVariants-1.6.1+1.21.4-Fabric.jar<br>
MoreBeehiveVariants-1.1.1+1.21.4-Fabric.jar<br>
MoreBookshelfVariants-1.0.6+1.21.4-Fabric.jar<br>
MoreCartographyTables-1.8.1+1.21.4-Fabric.jar<br>
morechathistory-1.3.1.jar<br>
MoreChestVariants-1.5.11+1.21.4-Fabric.jar<br>
MoreComposterVariants-1.8.1+1.21.4-Fabric.jar<br>
MoreCraftingTables-1.2.10+1.21.4-Fabric.jar<br>
moreculling-fabric-1.21.4-1.2.9.jar<br>
morediscs-1.21.4-34-fabric.jar<br>
MoreFeedingTroughVariants-1.1.0+1.21.4-Fabric.jar<br>
MoreFishingRodVariants-1.1.1+1.21.4-Fabric.jar<br>
MoreFletchingTables-1.8.2+1.21.4-Fabric.jar<br>
MoreGrindstoneVariants-1.1.3+1.21.4(5)-Fabric.jar<br>
MoreJukeboxNoteblockVariants-1.0.3+1.21.4-Fabric.jar<br>
MoreLecternVariants-1.8.2+1.21.4-Fabric.jar<br>
MoreLoomVariants-1.2.0+1.21.4-Fabric.jar<br>
MoreShieldVariants-1.3.10+1.21.4-Fabric.jar<br>
MoreSmithingTables-1.2.0+1.21.4-Fabric.jar<br>
MoreSmokerVariants-1.3.3+1.21.4(5)-Fabric.jar<br>
MoreStickVariants-1.4.2+1.21.4-Fabric.jar<br>
MoreToolVariants-1.1.2+1.21.4-Fabric.jar<br>
MoreTorchVariants-1.1.4+1.21.4-Fabric.jar<br>
morezombievillagers-1.21.4-3.6.jar<br>
more_mobs-v1.5.4-mc1.14x-1.21x-mod.jar<br>
mostructures-fabric-1.5.1+1.21.4.jar<br>
MouseTweaks-fabric-mc1.21.3-2.27.jar<br>
MRU-1.0.8+1.21.4+fabric.jar<br>
music-sync-1.4+1.21.4.jar<br>
mvs-4.3.4-1.21.4.jar<br>
namepain-1.5.3 fabric-1.21.2.jar<br>
nametagtweaks-1.21.4-4.0.jar<br>
nethermap-4.1.0-1.21.4.jar<br>
netherportalspread-1.21.4-8.4.jar<br>
noanimaltemptdelay-1.21.4-1.2.jar<br>
NoChatReports-FABRIC-1.21.4-v2.11.0.jar<br>
nofeathertrample-1.21.4-1.3.jar<br>
nohostilesaroundcampfire-1.21.4-7.2.jar<br>
noisium-fabric-2.5.0+mc1.21.4.jar<br>
NoRefreshScroll-1.21.4-1.0.11.jar<br>
notenoughanimations-fabric-1.9.2-mc1.21.4.jar<br>
Nullscape_1.21.x_v1.2.10.jar<br>
nutritiousmilk-1.21.4-3.5.jar<br>
OctoLib-FABRIC-0.5.0.1+1.21.4.jar<br>
Oh-The-Biomes-Weve-Gone-Fabric-3.0.1.jar<br>
Oh-The-Trees-Youll-Grow-fabric-1.21.4-6.0.3.jar<br>
online-emotes-3.3.3.1+mc1.21.4-fabric.jar<br>
OnlyHammers-1.21.4-0.1.jar<br>
optigui-2.3.0-beta.7+1.21.2.jar<br>
oreharvester-1.21.4-1.5.jar<br>
owo-lib-0.12.20+1.21.4.jar<br>
packetfixer-fabric-2.1.1-1.21.4.jar<br>
paginatedadvancements-2.6.1+1.21.4.jar<br>
particle_core-0.2.5+1.21.4.jar<br>
particular-1.1.1+1.21.4.jar<br>
petnames-1.21.4-3.5.jar<br>
PhilipsRuins1.21.4-2.1[Fabric].jar<br>
PickUpNotifier-v21.4.0-1.21.4-Fabric.jar<br>
piglinnames-1.21.4-1.3.jar<br>
Ping-Wheel-1.10.1-fabric-1.21.4.jar<br>
placeableblazerods-1.21.4-3.9.jar<br>
polytone-1.21.4-3.3.2-fabric.jar<br>
PresenceFootsteps-1.11.0+1.21.4.jar<br>
Prism-1.21.4-fabric-1.0.10.jar<br>
promenade-v5.0.0.jar<br>
puzzle-fabric-2.0.4+1.21.4.jar<br>
PuzzlesLib-v21.4.12-1.21.4-Fabric.jar<br>
qraftys-end-villages-3.1.jar<br>
qraftys-japanese-villages-3.1.jar<br>
qraftys-jungle-villages-4.jar<br>
Quad-1.2.11+1.21.4-Fabric.jar<br>
randombonemealflowers-1.21.4-4.7.jar<br>
randomvillagenames-1.21.4-3.8.jar<br>
real-arrow-tip-0.1.1+mc1.21.4.jar<br>
realisticbees-1.21.4-4.1.jar<br>
reeses-sodium-options-fabric-1.8.3+mc1.21.4.jar<br>
reinforced-chests-3.3.0+1.21.4.jar<br>
repurposed_structures-7.5.15+1.21.4-fabric.jar<br>
resourcepackchecker-fabric-1.21.4-1.2.2.jar<br>
respawnablepets-1.21.4-r1.jar<br>
respawningshulkers-1.21.4-4.1.jar<br>
RoguelikeDungeons-2.0.11-1.21.4-fabric.jar<br>
rrls-5.1.1+mc1.21.4-fabric.jar<br>
scaffoldingdropsnearby-1.21.4-3.4.jar<br>
scorched-1.1.4b.jar<br>
Searchables-fabric-1.21.4-1.0.3.jar<br>
seasonhud-fabric-1.21.4-1.12.5.jar<br>
SereneSeasons-fabric-1.21.4-10.4.0.6.jar<br>
servercore-fabric-1.5.8+1.21.4.jar<br>
serversleep-datapack2.jar<br>
ShoulderSurfing-Fabric-1.21.4-4.10.2.jar<br>
simple-armor-hud-1.21.4-1.5.1.jar<br>
sit-1.21.3-29.jar<br>
skeletonhorsespawn-1.21.4-4.1.jar<br>
skinlayers3d-fabric-1.7.4-mc1.21.4.jar<br>
smoothscroll-2.2.2.1.jar<br>
SnowUnderTrees-2.7.0+1.21.4.jar<br>
snowyleavesplus-mc1.21.4.jar<br>
snowysniffer-fabric-1.21.4-1.0.0.jar<br>
snuffles-1.4.0+1.21.4.jar<br>
sodium-extra-fabric-0.6.1+mc1.21.4.jar<br>
sodium-fabric-0.6.10+mc1.21.4.jar<br>
softerhaybales-1.21.4-3.4.jar<br>
soul-fire-d-fabric-1.21.4-5.1.6.jar<br>
sound-physics-remastered-fabric-1.21.4-1.4.8.jar<br>
sparkle-2.2.0.jar<br>
sparsestructures-fabric-1.21.4-2.2.1.jar<br>
spidersproducewebs-1.21.4-3.6.jar<br>
spookydoors-fabric-1.21.4-21.4.4.jar<br>
stack-to-nearby-chests-mc1.21.4-0.5.12.jar<br>
status-effect-bars-1.0.7.jar<br>
strayed-fates-forsaken-v2.0.0.2.jar<br>
strayspawn-1.21.4-3.7.jar<br>
Structory_1.21.x_v1.3.9.jar<br>
styledplayerlist-3.6.0+1.21.2.jar<br>
suggestion-tweaker-1.20.6-1.5.2-fabric.jar<br>
superbsteeds-1.21.4-r2.jar<br>
supermartijn642configlib-1.1.8-fabric-mc1.21.jar<br>
supermartijn642corelib-1.1.18a-fabric-mc1.21.4.jar<br>
surfacemushrooms-1.21.4-3.6.jar<br>
TaxFreeLevels-1.4.7-fabric-1.21.3.jar<br>
tcdcommons-3.12.7+fabric-1.21.4.jar<br>
TerraBlender-fabric-1.21.4-4.3.0.2.jar<br>
Terralith_1.21.x_v2.5.8.jar<br>
tia-fabric-1.21.3-1.2.2.jar<br>
tidal-towns-1.3.4.jar<br>
TierTagger-1.13.2+mc1.21.4.jar<br>
tnt-timer-3.0.jar<br>
tool-trims-packaged-v2.3.0a.jar<br>
toomanypaintings-24.11.29-1.21.3-fabric.jar<br>
totally_lit-1.1.0+1.21.4.jar<br>
trade-cycling-fabric-1.21.4-1.0.17.jar<br>
trimmable_tools-fabric-1.21.4-2.0.5.jar<br>
true-ending-v1.1.3.jar<br>
t_and_t-fabric-neoforge-1.13.5.jar<br>
ukulib-1.6.0+1.21.4.jar<br>
ukus-armor-hud-0.7.0+mc1.21.4.jar<br>
UniversalBoneMeal-v21.4.0-1.21.4-Fabric.jar<br>
UniversalEnchants-v21.4.1-1.21.4-Fabric.jar<br>
universal_ores-v1.7.0.jar<br>
videotape-1.5.0.jar<br>
village-map-on-start-1.1.jar<br>
villagerdeathmessages-1.21.4-3.6.jar<br>
villagernames-1.21.4-8.2.jar<br>
vinurl-1.4.0+mc1.21.4.jar<br>
VisibleTraders-0.0.7.1.jar<br>
visuality-0.7.9+1.21.4.jar<br>
visualoverhaul-fabric-6.0.0.jar<br>
VisualWorkbench-v21.4.1-1.21.4-Fabric.jar<br>
vmp-fabric-mc1.21.4-0.2.0+beta.7.192-all.jar<br>
voicechat-fabric-1.21.4-2.5.28.jar<br>
void_lib-1.1.6.jar<br>
watut-fabric-1.21.4-1.2.5.jar<br>
waveycapes-fabric-1.5.1-mc1.21.4.jar<br>
waystones-fabric-1.21.4-21.4.10.jar<br>
weaponmaster_ydm-fabric-1.21.4-4.2.7.jar<br>
welcomemessage-1.21.4-2.7.jar<br>
WilderWild-4.0.1-mc1.21.4.jar<br>
worldplaytime-1.2.4-1.21.4-FABRIC.jar<br>
xlpackets-1.0.5-1.21.jar<br>
yeetusexperimentus-fabric-87.0.0.jar<br>
yet_another_config_lib_v3-3.6.3+1.21.4-fabric.jar<br>
yosbr-0.1.2.jar<br>
your-reputation-0.2.10+jade.1.21.4.jar<br>
zombiehorsespawn-1.21.4-5.2.jar<br>
zombieproofdoors-1.21.4-3.5.jar<br>
zombievillagersfromspawner-1.21.4-3.9.jar<br>
Zoomify-2.14.2+1.21.3.jar<br>
[fabric]ctov-3.5.6.jar<br>
```
