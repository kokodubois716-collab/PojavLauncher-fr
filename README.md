🔵 MeyzLauncher

<h1 align="center">🔷 MeyzLauncher</h1><p align="center">
  <img src="assets/meyzlauncher.png" width="140" alt="MeyzLauncher Logo">
</p><p align="center">
  <strong>Minecraft Java Edition sur Android, à ta façon.</strong>
</p><p align="center">
  Un launcher Android inspiré de PojavLauncher, avec l'identité MeyzLauncher.
</p><p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-2196F3?style=for-the-badge&logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/Game-Minecraft%20Java-1976D2?style=for-the-badge&logo=minecraft&logoColor=white" alt="Minecraft Java">
  <img src="https://img.shields.io/badge/Project-MeyzLauncher-1565C0?style=for-the-badge" alt="MeyzLauncher">
</p>---

📖 Présentation

MeyzLauncher est un projet de launcher Android destiné à permettre le lancement de Minecraft: Java Edition sur les appareils Android compatibles.

Le projet est basé sur le code source de PojavLauncher et vise à proposer une expérience personnalisée sous l'identité MeyzLauncher.

✨ Fonctionnalités

- 🎮 Lancement de Minecraft: Java Edition sur Android.
- 🧩 Prise en charge des versions et fonctionnalités héritées du projet de base, selon leur compatibilité.
- ⚙️ Configuration des paramètres de lancement.
- 🎨 Identité visuelle personnalisée MeyzLauncher.
- 📱 Interface adaptée aux appareils Android.
- 🛠️ Possibilité d'évolution grâce aux contributions de la communauté.

«Les fonctionnalités disponibles dépendent de la version du code source utilisée et des modifications apportées au projet.»

📥 Télécharger MeyzLauncher

Les versions compilées seront publiées dans la section Releases du dépôt GitHub.

- Releases : "Télécharger MeyzLauncher" (https://github.com/TON-PSEUDO/MeyzLauncher/releases)
- Code source : "Consulter le dépôt" (https://github.com/TON-PSEUDO/MeyzLauncher)
- Compilation automatique : "GitHub Actions" (https://github.com/TON-PSEUDO/MeyzLauncher/actions)

Remplace "TON-PSEUDO" par ton nom d'utilisateur GitHub et "MeyzLauncher" par le nom exact de ton dépôt si nécessaire.

🏗️ Compilation

Prérequis

- Git
- Android SDK
- JDK compatible avec le projet
- Gradle Wrapper fourni avec le dépôt
- Les dépendances et composants nécessaires au projet

Compilation rapide

1. Clone le dépôt :
   
   git clone https://github.com/TON-PSEUDO/MeyzLauncher.git
cd MeyzLauncher

2. Lance la compilation :
   
   ./gradlew :app_pojavlauncher:assembleDebug
   
   Sous Windows, utilise :
   
   gradlew.bat :app_pojavlauncher:assembleDebug

3. Une fois la compilation terminée, recherche l'APK dans :
   
   app_pojavlauncher/build/outputs/apk/debug/

Important : ces commandes supposent que le projet conserve la structure de modules de PojavLauncher. Si les noms des modules ont changé, adapte la commande au projet.

Compilation automatique avec GitHub Actions

Une compilation Android peut être automatisée avec un workflow GitHub Actions.

Le workflow doit notamment :

1. Récupérer le code source.
2. Installer la version appropriée du JDK.
3. Configurer Android SDK.
4. Accorder les permissions nécessaires au Gradle Wrapper.
5. Compiler l'APK.
6. Publier l'APK comme artefact téléchargeable.

📊 État du projet

Fonctionnalité| État
Base du launcher| Héritée de PojavLauncher
Identité MeyzLauncher| En personnalisation
Logo bleu| À intégrer dans le projet
Interface personnalisée| Selon les modifications
Compilation APK| À vérifier
Tests sur appareils Android| À effectuer
Publication des releases| Selon l'avancement

Cette liste doit être mise à jour au fur et à mesure du développement.

🐛 Problèmes connus

Si tu rencontres un problème :

1. Vérifie la version de Minecraft utilisée.
2. Vérifie que l'appareil dispose de suffisamment de mémoire.
3. Consulte les journaux du launcher.
4. Vérifie la compatibilité des mods et des bibliothèques.
5. Ouvre une issue GitHub en fournissant les informations utiles.

Pour signaler un problème :

"Créer une issue" (https://github.com/TON-PSEUDO/MeyzLauncher/issues)

🤝 Contributions

Les contributions sont les bienvenues.

Tu peux contribuer en :

- Signalant des bugs.
- Proposant des améliorations.
- Améliorant l'interface.
- Participant aux traductions.
- Testant les versions compilées.
- Soumettant des pull requests.

Toute modification doit respecter la licence du code concerné ainsi que les licences des composants utilisés.

📜 Licence

MeyzLauncher est un projet dérivé de PojavLauncher.

Le projet d'origine est distribué sous la licence GNU LGPL v3, mais les fichiers et dépendances peuvent avoir des licences différentes.

Consulte les fichiers "LICENSE" et les notices de copyright du dépôt d'origine avant de distribuer une version modifiée.

"Licence PojavLauncher" (https://github.com/PojavLauncherTeam/PojavLauncher/blob/v3_openjdk/LICENSE)

🙏 Crédits

MeyzLauncher s'appuie sur le travail des développeurs et contributeurs des projets utilisés.

Crédits aux projets d'origine :

- "PojavLauncher" (https://github.com/PojavLauncherTeam/PojavLauncher) — projet de base.
- "Boardwalk" (https://github.com/zhuowei/Boardwalk) — projet historique.
- "LWJGL" (https://github.com/LWJGL/lwjgl3) — bibliothèques de jeu.
- "GL4ES" (https://github.com/PojavLauncherTeam/gl4es) — compatibilité graphique.
- "OpenJDK" (https://openjdk.org/) — environnement Java.
- Tous les autres contributeurs et mainteneurs des bibliothèques utilisées.

Les marques Minecraft et Mojang appartiennent à leurs propriétaires respectifs. MeyzLauncher est un projet indépendant et n'est pas affilié officiellement à Mojang ou Microsoft.

🚀 Feuille de route

Les objectifs envisagés pour MeyzLauncher :

- [ ] Finaliser l'identité visuelle bleue.
- [ ] Personnaliser l'écran d'accueil.
- [ ] Améliorer l'expérience utilisateur sur Android.
- [ ] Vérifier la compatibilité avec les différentes versions de Minecraft.
- [ ] Tester les performances sur les appareils modestes.
- [ ] Automatiser la compilation des APK.
- [ ] Publier des versions stables.
- [ ] Étudier de nouvelles possibilités de personnalisation.

---

<p align="center">
  <strong>🔵 MeyzLauncher</strong><br>
  <em>Minecraft Java Edition, partout où Android le permet.</em>
</p>