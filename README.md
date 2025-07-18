# 🎮 Minecraft Pearadise V2

## 📜 Liste des commandes disponibles

### 🎮 Commandes de base

| Commande                  | Description                                                       |
| ------------------------- | ----------------------------------------------------------------- |
| `/msg <joueur> <message>` | Envoie un message privé à un joueur.                              |
| `/help`                   | Affiche la liste des commandes disponibles.                       |
| `/itemlore <texte>`       | Ajoute ou modifie la description (lore) d’un objet.               |
| `/hat`                    | Place l’objet tenu dans votre main sur votre tête.                |
| `/playtime <joueur>`      | Affiche le temps de jeu total d’un joueur.                        |
| `/ping`                   | Répond “Pong” pour tester la latence.                             |
| `/recipe <item>`          | Affiche la recette de fabrication d’un objet.                     |
| `/msgtoggle`              | Active ou désactive la réception des messages privés.             |
| `/list`                   | Affiche la liste des joueurs actuellement en ligne.               |
| `/ignore <joueur>`        | Ignore ou réactive l’affichage des messages d’un joueur.          |
| `/realname <pseudo>`      | Affiche le pseudo réel d’un joueur « nicknamé ».                  |
| `/rtoggle`                | Définit si `/r` répond au dernier message reçu ou envoyé.         |
| `/gameruleslist`          | Affiche les règles du serveur (gamerules).                        |
| `/stats`                  | Affiche vos statistiques personnelles.                            |
| `/r`                      | Répond au dernier message reçu.                                   |
| `/axgrave list`           | Affiche la liste de vos tombes (plugin AxGraves).                 |
| `/plugins`                | Affiche la liste des plugins actifs sur le serveur.               |
| `/version`                | Affiche la version du serveur.                                    |
| `/discord`                | Affiche le lien vers notre Discord communautaire.                 |
| `/tps`                    | Affiche le TPS (tick rate) actuel du serveur.                     |
| `/sparktps`               | Même chose, avec les statistiques Spark.                          |

> ℹ️ **Note**  
> - Commandes accessibles à tous les joueurs (pas besoin d’admin).  

---

### 🖼️ Commandes ImageFrame

| Commande                                                        | Description                                                                                                                                                        |
| --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `/imageframe create <nom> <url> <largeur> <hauteur> [combined]` | Crée l’image `<nom>` depuis l’URL `<url>`, aux dimensions indiquées (en blocs).<br>Optionnel : `combined` génère un **objet unique** (Combined ImageMap).          |
| `/imageframe delete <nom>`                                      | Supprime définitivement l’image nommée `<nom>`.                                                                                                                    |
| `/imageframe get <nom>`                                         | Donne dans votre inventaire l’image `<nom>` déjà créée.                                                                                                            |
| `/imageframe info`                                              | Affiche les détails de l’image en main (nom, dimensions, format, source…).                                                                                         |
| `/imageframe list`                                              | Liste toutes les images créées par votre compte sur le serveur.                                                                                                    |
| `/imageframe overlay <nom> <url>`                               | Superpose une image semi-transparente `<nom>` sur la carte que vous tenez.                                                                                         |
| `/imageframe preference`                                        | Affiche ou modifie vos préférences d’affichage (animation, cache…).                                                                                                |

> ℹ️ **Note**  
> - Ces commandes requièrent au moins une carte vide dans l’inventaire.  

---

### ⚔️ Commandes Gorosei (modération)

> **Permissions**  
> Nécessite le rôle Gorosei.

| Commande       | Description                                                  |
| -------------- | ------------------------------------------------------------ |
| `/ban`         | Bannit définitivement un joueur.                             |
| `/banip`       | Bannit une adresse IP ou un joueur par IP.                   |
| `/kick`        | Expulse un joueur du serveur.                                |
| `/kickall`     | Expulse tous les joueurs (sauf l’émetteur).                  |
| `/mute`        | Coupe le chat d’un joueur (retape `/mute` pour rétablir).    |
| `/nick`        | Change le pseudo affiché d’un joueur.                        |
| `/tempban`     | Bannit temporairement un joueur.                             |
| `/tempbanip`   | Bannit temporairement une IP ou un joueur par IP.            |
| `/unban`       | Retire un bannissement par pseudo.                           |
| `/unbanip`     | Retire un bannissement par IP.                               |
| `/whitelist`   | Gère la liste blanche (`on`/`off`, `add`, `remove`, `list`). |

---

## 🧩 Contenu du serveur

### 🛠️ Plateforme

| Plateforme | Version   | Lien                                             |
| ---------- | --------- | ------------------------------------------------ |
| PaperMC    | 1.21.8-4  | [papermc.io](https://papermc.io/downloads/paper) |

### 🔌 Plugins

| Plugin                | Version        | Lien                                                                  |
| --------------------- | -------------- | --------------------------------------------------------------------- |
| AxGraves              | 1.22.3         | [Modrinth](https://modrinth.com/plugin/axgraves)                      |
| Chunky                | 1.4.40         | [Modrinth](https://modrinth.com/plugin/chunky)                        |
| ConsoleSpamFixReborn  | 1.11.6         | [Modrinth](https://modrinth.com/plugin/console-spam-fix-reborn)       |
| CoreProtect           | 22.4           | [GitHub](https://github.com/PlayPro/CoreProtect)                      |
| EssentialsX           | 2.21.2-dev+29  | [essentialsx.net](https://essentialsx.net/downloads.html)             |
| EssentialsXChat       | 2.21.2-dev+29  | [essentialsx.net](https://essentialsx.net/downloads.html)             |
| EssentialsXDiscord    | 2.21.2-dev+29  | [essentialsx.net](https://essentialsx.net/downloads.html)             |
| ImageFrame            | 1.8.4          | [Modrinth](https://modrinth.com/plugin/imageframe)                    |
| LuckPerms             | 5.5.9          | [luckperms.net](https://luckperms.net/download)                       |
| ProAntiTab            | 1.9.1          | [Modrinth](https://modrinth.com/plugin/proantitab)                    |
| VaultUnlocked         | 2.14.0         | [Modrinth](https://modrinth.com/plugin/vaultunlocked)                 |
| WorldEdit             | 7.3.15         | [Modrinth](https://modrinth.com/plugin/worldedit)                     |
| XaeroForceDisabler    | 1.3            | [Modrinth](https://modrinth.com/plugin/drqads-xaero-force-disabler)   |

### 📦 Datapacks

| Datapack                            | Version | Lien                                                                                             |
| ----------------------------------- | ------- | ------------------------------------------------------------------------------------------------ |
| All Mob Heads                       | 10.13   | [CurseForge](https://www.curseforge.com/minecraft/customization/all-mob-heads)                   |
| DnT Ancient City Overhaul           | 3.1     | [Modrinth](https://modrinth.com/datapack/dungeons-and-taverns-ancient-city-overhaul)             |
| DnT End Castle Standalone           | 1.3.4   | [Modrinth](https://modrinth.com/datapack/dungeons-and-taverns-end-castle-standalone)             |
| DnT Jungle Temple Overhaul          | 2       | [Modrinth](https://modrinth.com/datapack/dungeons-and-taverns-jungle-temple-overhaul)            |
| DnT Nether Fortress Overhaul        | 3       | [Modrinth](https://modrinth.com/datapack/dungeons-and-taverns-nether-fortress-overhaul)          |
| DnT Ocean Monument Overhaul         | 2       | [Modrinth](https://modrinth.com/datapack/dungeons-and-taverns-ocean-monument-overhaul)           |
| DnT Pillager Outpost Overhaul       | 3.2.1   | [Modrinth](https://modrinth.com/datapack/dungeons-and-taverns-pillager-outpost-overhaul)         |
| DnT Stronghold Overhaul             | 2.3.1   | [Modrinth](https://modrinth.com/datapack/dungeons-and-taverns-stronghold-overhaul)               |
| DnT Swamp Hut Overhaul              | 2.2     | [Modrinth](https://modrinth.com/datapack/dungeons-and-taverns-swamp-hut-overhaul)                |
| DnT Woodland Mansion Replacement    | 1.6.1   | [Modrinth](https://modrinth.com/datapack/dungeons-and-taverns-woodland-mansion-replacement)      |
| Dungeons and Taverns                | 4.7.3   | [Modrinth](https://modrinth.com/datapack/dungeons-and-taverns)                                   |
| Explorify                           | 1.6.2   | [Modrinth](https://modrinth.com/datapack/explorify)                                              |
| Ghast Pedal!*                       | 1.0     | [CurseForge](https://modrinth.com/datapack/ghast-pedal)                                          |
| Hopo Better Underwater Ruins        | 1.2.4   | [Modrinth](https://modrinth.com/datapack/hopo-better-underwater-ruins)                           |
| Minecart Improvements               | 1.21.7  | [minecraft.wiki](https://minecraft.wiki/w/Minecart_Improvements)                                 |
| Structory                           | 1.3.11  | [Modrinth](https://modrinth.com/datapack/structory)                                              |
| Terralith                           | 2.5.11  | [Modrinth](https://modrinth.com/datapack/terralith)                                              |
| Terratonic                          | 3.0     | [Modrinth](https://modrinth.com/datapack/terratonic)                                             |
| Tool Trims                          | 2.3.3a  | [Modrinth](https://modrinth.com/datapack/tool-trims)                                             |
| True Ending – Ender Dragon Overhaul | 1.1.4b  | [Modrinth](https://modrinth.com/datapack/true-ending)                                            |
| Vanilla Refresh                     | 1.4.27g | [Modrinth](https://modrinth.com/datapack/vanilla-refresh)                                        |
| Vanilla Tweaks - Armor Statues      | 2.8.19  | [vanillatweaks.net](https://vanillatweaks.net/picker/datapacks/)                                 |
| Vanilla Tweaks - Mini Blocks        | 1.1.3   | [vanillatweaks.net](https://vanillatweaks.net/picker/datapacks/)                                 |
| Vanilla Tweaks - TrackRawStatistics | 1.7.9   | [vanillatweaks.net](https://vanillatweaks.net/picker/datapacks/)                                 |
| Vanilla Tweaks - Track Statistics   | 1.1.15  | [vanillatweaks.net](https://vanillatweaks.net/picker/datapacks/)                                 |
| Vanilla Tweaks - Unlock All Recipes | 2.0.14  | [vanillatweaks.net](https://vanillatweaks.net/picker/datapacks/)                                 |
| Vanilla Tweaks Crafting Tweaks**    | 2.0.14  | [vanillatweaks.net](https://vanillatweaks.net/picker/crafting-tweaks/)                           |

\* J’ai modifié le datapack: l’augmentation de la vitesse était initialement de 30 %, elle est désormais de 40 % <br>
\** (unpackable ice, straight to shapeless, more bark, more stairs & more bricks)

### 🎨 Resource Packs

| Resource Pack                     | Version | Lien                                                                         |
| --------------------------------- | ------- | ---------------------------------------------------------------------------- |
| Tool Trims (Textures)             | 2.3.3   | [Modrinth](https://modrinth.com/datapack/tool-trims)                         |
| True Ending: Ender Dragon Music   | 1.0     | [Modrinth](https://modrinth.com/resourcepack/true-ending-ender-dragon-music) |
| Terralith Language Fix            | 1.1.0   | [Modrinth](https://modrinth.com/resourcepack/terralith-lang)                 |