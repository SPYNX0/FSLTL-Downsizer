# FSLTL Downsizer

**Lighter FSLTL traffic textures for Microsoft Flight Simulator 2024: less VRAM, less disk space.**
*Des textures plus légères pour le trafic FSLTL de MSFS 2024 : moins de mémoire vidéo, moins d'espace disque.*

## ⬇️ Download / Télécharger

👉 **[Latest version / Dernière version](https://github.com/SPYNX0/FSLTL-Downsizer/releases/latest)** : download `FSLTL-Downsizer-Setup-x.y.z.exe`.


## English

The FSLTL Traffic Base package weighs around 50 GB, mostly 4K liveries that AI traffic rarely needs. FSLTL Downsizer makes a copy of it with smaller textures, ready to drop into your Community folder.

- **Finds FSLTL by itself** in your MSFS 2024 Community folder (Microsoft Store or Steam), including through links and sub-folders.
- **Installs and updates FSLTL** from its official release: full, or directly with reduced textures (the full package is never stored). Only what changed is downloaded, every file is checked, and downloads can be resumed.
- **Three sizes**: 2K, 1K (recommended) or 512, with the expected result shown before you start.
- **No quality loss** for textures that have mipmaps (almost all of them): their smaller versions are already inside, FSLTL Downsizer keeps them byte for byte, in their original format. The few others are re-encoded in their original format with Microsoft's texconv.
- **Your original package is never modified.** The export is a complete package: `layout.json` and `manifest.json` are updated for the reduced textures.
- **Hard links** on the same drive: unchanged files take no extra space.
- **Resume and incremental updates**: stop any time and resume later; after an FSLTL update, only new or changed files are processed.
- English / French interface, in-app updates.

**Use it:** pick the size, pick a destination, then replace `fsltl-traffic-base` in your Community folder with the new folder. Never keep both at the same time.

> Windows may show *"Windows protected your PC"* the first time (the installer isn't code-signed): click **More info → Run anyway**.

Requirements: Windows 10/11 64-bit, MSFS 2024, FSLTL Traffic Base.

## Français

Le pack FSLTL Traffic Base pèse environ 50 Go, surtout des livrées en 4K dont le trafic IA a rarement besoin. FSLTL Downsizer en crée une copie aux textures réduites, prête à placer dans votre dossier Community.

- **Trouve FSLTL tout seul** dans le dossier Community de MSFS 2024 (Microsoft Store ou Steam), y compris via des liens et des sous-dossiers.
- **Installe et met à jour FSLTL** depuis sa release officielle : complet, ou directement avec des textures réduites (le pack complet n'est jamais stocké). Seul ce qui a changé est téléchargé, chaque fichier est vérifié et le téléchargement peut être repris.
- **Trois tailles** : 2K, 1K (recommandé) ou 512, avec le résultat attendu affiché avant de commencer.
- **Aucune perte de qualité** pour les textures qui ont des mipmaps (presque toutes) : leurs versions réduites sont déjà à l'intérieur, FSLTL Downsizer les garde à l'octet près, dans leur format d'origine. Les quelques autres sont réencodées dans leur format d'origine avec texconv de Microsoft.
- **Votre pack d'origine n'est jamais modifié.** L'export est un package complet : `layout.json` et `manifest.json` sont mis à jour pour les textures réduites.
- **Liens physiques** sur le même disque : les fichiers inchangés ne prennent pas de place en plus.
- **Reprise et mises à jour incrémentales** : arrêtez quand vous voulez et reprenez plus tard ; après une mise à jour de FSLTL, seuls les fichiers nouveaux ou modifiés sont traités.
- Interface en français / anglais, mises à jour dans l'app.

**Utilisation :** choisissez la taille, la destination, puis remplacez `fsltl-traffic-base` dans votre dossier Community par le nouveau dossier. Ne gardez jamais les deux en même temps.

> Windows peut afficher *« Windows a protégé votre ordinateur »* la première fois (l'installeur n'est pas signé) : cliquez sur **Informations complémentaires → Exécuter quand même**.

Configuration : Windows 10/11 64 bits, MSFS 2024, FSLTL Traffic Base.

---

FSLTL Downsizer is not affiliated with FSLTL or Microsoft. Don't redistribute the packages it produces.
*FSLTL Downsizer n'est pas affilié à FSLTL ni à Microsoft. Ne redistribuez pas les packages produits.*

© 2026 Spynxo. All rights reserved. Free for personal use, see [LICENSE](LICENSE.txt).
