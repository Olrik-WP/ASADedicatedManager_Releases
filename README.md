# ASA Dedicated Server Manager

## Introduction

ASA Dedicated Server Manager is an innovative application designed to simplify the management and configuration of dedicated servers for "Ark Survival Ascended". This robust and user-friendly tool offers an intuitive interface for managing the game's complex settings, making server experience more enjoyable and accessible.

## Screenshot

![Screenshot](https://image.noelshack.com/fichiers/2023/51/5/1703269756-asadm3.jpg)

## Prerequisites

Before using ASA Dedicated Server Manager, ensure that your system meets the following requirements:

- [.NET Framework 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-web-installer) or higher installed on your system.

Download and install it from the provided link if it's not already installed on your system.

## Existing Servers

ASA Dedicated Server Manager is designed for flexibility. If you already have an existing server, you can easily integrate it with our manager:

- Simply select the folder of your existing server. 
- The program will perform a check to see if the necessary files are present. (the ShooterGame folder must be present in a folder: server and steamcmd.exe must be present in the steamcmd folder)
![Screenshot](https://i.ibb.co/SRcq3mz/server.jpg)
- If the files are found, they will be used; if not, you have the option to install a new server.
- this will be reworked in a future update

This makes it effortless to switch between managing an existing server and setting up a new one.

## Key Features

### Automatic Configuration Object Construction
- **Adaptability to ASA Updates:**
A major strength of ASA Dedicated Server Manager lies in its ability to automatically construct configuration objects based on GameUserSettings.ini and Game.ini files. This ensures that the tool remains relevant and effective even with rapid changes in ASA, without requiring code modifications.

- **Full Feature Support:**
Full Feature Support: The smart design of the application ensures full support for the latest ASA features and settings, providing users with the flexibility to adapt their servers to the newest game updates.

### Intuitive User Interface
- **Easy Settings Management:**
With a clear and well-organized interface, users can easily navigate and modify server settings, from gameplay adjustments to advanced configurations.

### Integrated Translations
- **International Accessibility:**
Integrated translations for configuration file descriptions allow users worldwide to understand and manipulate server settings in their own language, making the tool accessible to a broader audience. More translation to come. Currently English and French

### Additional Features
- **Efficient Search and Save:**
Users can quickly search for specific settings and save their configurations, enabling easy and safe server customization.

- **Update and Mod Support:**
ASA Dedicated Server Manager facilitates server updating and mod additions, ensuring that servers stay up-to-date with the latest ASA content and features.

## Why Choose ASA Dedicated Server Manager?

ASA Dedicated Server Manager is more than just a server management tool. It is a comprehensive solution that combines flexibility, ease of use, and adaptability. Whether you're an experienced server admin or a newcomer, this tool provides everything you need to manage your ASA dedicated server effectively. With ASA Dedicated Server Manager, you're always prepared for the adventure, no matter the changes the game may undergo.

## Upcoming Updates

ASA Dedicated Server Manager is constantly evolving. In upcoming updates, we will be addressing the following options:

- LevelExperienceRampOverrides
- OverrideEngramEntries
- OverrideNamedEngramEntries
- EngramEntryAutoUnlocks
- DinoSpawnWeightMultipliers
- DinoClassResistanceMultipliers
- TamedDinoClassResistanceMultipliers
- DinoClassDamageMultipliers
- TamedDinoClassDamageMultipliers
- HarvestResourceItemAmountClassMultipliers
- NPCReplacements
- ConfigOverrideItemCraftingCosts
- ConfigOverrideItemMaxQuantity
- ConfigOverrideSupplyCrateItems
- ConfigOverrideNPCSpawnEntriesContainer
- ConfigAddNPCSpawnEntriesContainer
- ConfigSubtractNPCSpawnEntriesContainer

Additional advanced configurations will also be included:

- OverridePlayerLevelEngramPoints
- MutagenLevelBoost[<Stat_ID>]
- MutagenLevelBoost_Bred[<Stat_ID>]
- PerLevelStatsMultiplier_Player[<integer>]
- PerLevelStatsMultiplier_DinoTamed<_type>[<integer>]
- PerLevelStatsMultiplier_DinoWild[<integer>]
- PlayerBaseStatMultipliers[<attribute>]
- ItemStatClamps[<attribute>]

## Future Features

- **Profile and World Data Backup and Restore**: Upcoming updates will include the capability to back up and restore player profiles and world data. This feature will ensure that server administrators can easily save and secure player progress and world, providing a safety net against data loss. With this feature, restoring your server to a specific point in time, including player progress and world state, will be just a few clicks away.

Stay tuned for these significant enhancements that aim to provide a complete and worry-free server management solution.

---

# Gestionnaire de Serveur Dédié ASA

## Introduction

ASA Dedicated Server Manager est une application robuste et innovante conçue pour la configuration et la gestion des serveurs dédiés pour le jeu Ark: Survival Ascended. Conçue avec flexibilité à l'esprit, cette application automatise la construction des objets à partir des fichiers de configuration `GameUserSettings.ini` et `Game.ini`, permettant une adaptation rapide aux changements fréquents du jeu.

Grâce à sa conception intuitive, ASA Dedicated Server Manager intègre des descriptions traduites des paramètres de configuration, offrant ainsi une expérience utilisateur améliorée pour les administrateurs de serveurs du monde entier. Cette fonctionnalité multilingue rend l'application accessible et facile à utiliser, peu importe votre langue maternelle.

## Captures d'Écran

![Screenshot](https://image.noelshack.com/fichiers/2023/51/5/1703269756-asadm3.jpg)

## Prérequis

Avant d'utiliser ASA Dedicated Server Manager, assurez-vous que votre système répond aux exigences suivantes :

- [.NET Framework 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-web-installer) ou supérieur installé sur votre système.

Téléchargez et installez-le à partir du lien fourni s'il n'est pas déjà installé sur votre système.

## Serveurs Existant

ASA Dedicated Server Manager est conçu pour être flexible. Si vous avez déjà un serveur existant, vous pouvez facilement l'intégrer avec notre gestionnaire :

- Sélectionnez simplement le dossier de votre serveur existant. (le dossier ShooterGame doit etre présent dans un dossier: server et steamcmd.exe doit etre présent dans le dossier steamcmd) 
![Screenshot](https://i.ibb.co/SRcq3mz/server.jpg)
- Le programme effectuera une vérification pour voir si les fichiers nécessaires sont présents.
- Si les fichiers sont trouvés, ils seront utilisés ; sinon, vous avez la possibilité d'installer un nouveau serveur.
- cela va être retravaillé dans une future mise à jour

Cela rend le passage de la gestion d'un serveur existant à la configuration d'un nouveau serveur sans effort.

## Fonctionnalités Principales

- **Construction Automatique des Objets de Configuration** : Les objets de configuration sont construits automatiquement à partir des fichiers `GameUserSettings.ini` et `Game.ini`, assurant une grande adaptabilité aux mises à jour du jeu.
- **Traductions Intégrées** : Les descriptions des paramètres de configuration sont traduites, rendant l'application facile à utiliser pour un public international.
- **Interface Utilisateur Intuitive** : Conçu pour une facilité d'utilisation maximale, permettant une gestion de serveur efficace et sans tracas.
- **Prêt pour l'Avenir** : Conçu pour s'adapter facilement aux changements et aux nouvelles fonctionnalités du jeu.
- **Support Multilingue** : L'interface utilisateur et les descriptions sont disponibles en plusieurs langues.

## Mises à Jour à Venir

ASA Dedicated Server Manager est en constante évolution. Dans les prochaines mises à jour, nous allons traiter les options suivantes :

- LevelExperienceRampOverrides
- OverrideEngramEntries
- OverrideNamedEngramEntries
- EngramEntryAutoUnlocks
- DinoSpawnWeightMultipliers
- DinoClassResistanceMultipliers
- TamedDinoClassResistanceMultipliers
- DinoClassDamageMultipliers
- TamedDinoClassDamageMultipliers
- HarvestResourceItemAmountClassMultipliers
- NPCReplacements
- ConfigOverrideItemCraftingCosts
- ConfigOverrideItemMaxQuantity
- ConfigOverrideSupplyCrateItems
- ConfigOverrideNPCSpawnEntriesContainer
- ConfigAddNPCSpawnEntriesContainer
- ConfigSubtractNPCSpawnEntriesContainer

Des configurations avancées supplémentaires seront également incluses :

- OverridePlayerLevelEngramPoints
- MutagenLevelBoost[<Stat_ID>]
- MutagenLevelBoost_Bred[<Stat_ID>]
- PerLevelStatsMultiplier_Player[<integer>]
- PerLevelStatsMultiplier_DinoTamed<_type>[<integer>]
- PerLevelStatsMultiplier_DinoWild[<integer>]
- PlayerBaseStatMultipliers[<attribute>]
- ItemStatClamps[<attribute>]

## Fonctionnalités Futures

- **Sauvegarde et Restauration des Profils de Joueurs et des Données du Monde** : Les mises à jour à venir incluront la capacité de sauvegarder et de restaurer les profils des joueurs et le monde. Cette fonctionnalité garantira que les administrateurs de serveurs peuvent facilement sauvegarder et sécuriser les progrès des joueurs et les configurations du monde, offrant un filet de sécurité contre la perte de données. Avec cette fonctionnalité, restaurer votre serveur à un moment spécifique, y compris la progression des joueurs et l'état du monde, sera à quelques clics.

Restez à l'écoute pour ces améliorations significatives qui visent à fournir une solution de gestion de serveur complète et sans souci.