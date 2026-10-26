<div align="center">

# 🌀 Brise

### Le contrôle des ventilateurs de votre PC, simple et sûr.

*Cinq modes en un clic, ou un réglage précis ventilateur par ventilateur.<br>Gratuit, en français, sans publicité.*

<br>

[![Télécharger](https://img.shields.io/badge/⬇_Télécharger-version_1.0.0-FF4FD8?style=for-the-badge&labelColor=12141B)](https://github.com/lerapeurdu62280-debug/Brise-Download/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#-configuration-requise)
[![Gratuit](https://img.shields.io/badge/Gratuit-sans_publicité-35E0F0?style=for-the-badge&labelColor=12141B)](#)
[![Discord](https://img.shields.io/badge/Discord-rejoindre_l%E2%80%99atelier-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=12141B)](https://discord.gg/W5hd36CW6b)

</div>

<br>

---

## ✨ Fonctionnalités

<table>
<tr>
<td width="50%" valign="top">

### 🎚️ Cinq modes en un clic
- **BIOS**, **Silencieux**, **Équilibré**, **Performance** et **Max**.
- Changement de mode depuis la fenêtre ou l'icône près de l'horloge.

</td>
<td width="50%" valign="top">

### 🛠️ Réglage par ventilateur
- **Auto** (le BIOS décide), **Fixe** (à partir de 20 %) ou **Courbe** selon la température du processeur, de la carte graphique ou la plus haute des deux.
- Vitesse en tr/min affichée en direct.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ Sécurité d'abord
- À **85 °C** ou plus, tous les ventilateurs passent à **100 %**.
- Capteur perdu, fermeture ou plantage : **le BIOS reprend la main**.

</td>
<td width="50%" valign="top">

### 🔕 Discret
- Démarrage automatique avec Windows, réduit près de l'horloge.
- La croix cache la fenêtre, Brise continue de veiller.

</td>
</tr>
</table>

<br>

## ⬇️ Télécharger

👉 **[Brise-Portable-1.0.0.zip](https://github.com/lerapeurdu62280-debug/Brise-Download/releases/latest)** : aucune installation, .NET est déjà inclus.

1. Décompressez le dossier.
2. Lancez **PawnIO_setup.exe** une seule fois (pilote officiel signé, nécessaire pour piloter les ventilateurs).
3. Lancez **Brise.exe** (droits administrateur demandés).

> Windows SmartScreen peut afficher « Windows a protégé votre ordinateur » : cliquez sur **Informations complémentaires**, puis **Exécuter quand même**.

<br>

## 💻 Configuration requise

- Windows 10 ou 11, 64 bits, compte administrateur.
- Un **PC fixe** dont la carte mère laisse piloter ses ventilateurs par logiciel : c'est le cas de la plupart des cartes ASRock, MSI, Gigabyte et Asus.

<br>

## ❓ Questions fréquentes

<details>
<summary><b>Brise fonctionne-t-il sur un PC portable ?</b></summary>
<br>
En général non : sur les portables, les ventilateurs sont gérés par le constructeur et ne se laissent pas piloter. C'est aussi souvent le cas des PC de marque (Dell, HP, Lenovo).
</details>

<details>
<summary><b>« Aucun ventilateur pilotable trouvé » : que faire ?</b></summary>
<br>
Vérifiez que PawnIO est installé (PawnIO_setup.exe, fourni dans le dossier), puis relancez Brise. Si le message reste, votre carte mère ne permet pas le pilotage par logiciel.
</details>

<details>
<summary><b>Et les ventilateurs de la carte graphique ?</b></summary>
<br>
Brise lit la température de la carte graphique pour ses courbes, mais ne pilote que les ventilateurs branchés sur la carte mère.
</details>

<details>
<summary><b>Comment arrêter Brise ?</b></summary>
<br>
Clic droit sur son icône près de l'horloge, puis <b>Quitter</b> : le BIOS reprend aussitôt la main.
</details>

<br>

---

<div align="center">

**S.O.S INFO LUDO** · Boulogne-sur-Mer

<sub>Logiciel gratuit, tous droits réservés. Composants tiers : LibreHardwareMonitorLib (MPL-2.0), pilote PawnIO (GPL-2.0, installeur officiel non modifié), polices Chakra Petch, Audiowide et Mr Dafoe (OFL).<br>Windows est une marque de Microsoft Corporation ; ASRock, MSI, Gigabyte, Asus, Dell, HP et Lenovo sont des marques de leurs propriétaires respectifs. Ce logiciel est indépendant.</sub>

</div>
