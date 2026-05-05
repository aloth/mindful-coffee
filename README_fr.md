🇺🇸 [English](README.md) | 🇩🇪 [Deutsch](README_de.md) | 🇪🇸 [Español](README_es.md) | 🇫🇷 **Français** | 🇯🇵 [日本語](README_ja.md) | 🇨🇳 [中文](README_zh-Hans.md)

# Mindful Coffee — Suivi de caféine et carnet d'extraction pour iPhone, iPad et Mac

[![App Store](https://img.shields.io/badge/App_Store-Télécharger-blue?logo=apple&logoColor=white)](https://apps.apple.com/fr/app/mindful-coffee-tracks-caffeine/id6742878005)
[![Swift](https://img.shields.io/badge/Swift-6.0-orange?logo=swift&logoColor=white)](https://swift.org)
[![Plateforme](https://img.shields.io/badge/Plateforme-iOS_17+-lightgrey?logo=apple)](https://developer.apple.com/ios/)
[![GitHub stars](https://img.shields.io/github/stars/aloth/mindful-coffee?style=social)](https://github.com/aloth/mindful-coffee/stargazers)

<p align="center">
  <img src="assets/images/mindful-coffee-caffeine-tracker-sleep-optimization-hero.png" alt="Mindful Coffee — suivi intelligent de la caféine avec prédiction du sommeil et optimisation du rythme du cortisol" width="700">
</p>

**Mieux extraire. Mieux dormir.**

Mindful Coffee est la seule app iOS qui réunit un véritable **carnet d'extraction** et un modèle personnel du métabolisme de la caféine, avec prédiction du sommeil entièrement sur l'appareil. Enregistrez chaque espresso, V60, AeroPress, Chemex, cold brew, matcha ou thé, sachez exactement quand la caféine sera éliminée et comprenez le rythme naturel du cortisol de votre corps. Conçue avec le langage de design **Liquid Glass** d'Apple. Elle fait partie de la famille **Mindful Apps**, aux côtés de [Mindful Body](https://github.com/aloth/mindful-body).

[![Télécharger sur l'App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/fr/app/mindful-coffee-tracks-caffeine/id6742878005?platform=iphone)

## Points forts

### ☕ Carnet d'extraction
Espresso, V60, AeroPress, Chemex, presse française, moka, cold brew, ainsi que thé, matcha et Gong Fu. Notez la mouture, la dose, le ratio, le temps, la température et la note dans un flux élégant. Recettes intégrées, suggestions intelligentes pour affiner plus vite et analytique pour identifier votre meilleure tasse.

### 🧬 Modèle cortisol et caféine
Un modèle personnel de demi-vie prédit quand la caféine sera éliminée et quand votre corps sera prêt à dormir. La vue du rythme du cortisol affiche votre courbe d'énergie naturelle pour caler votre café sur les fenêtres où il aide vraiment.

### ❤️ Body Insights depuis Apple Santé
Mettez en relation votre consommation de caféine et la réaction réelle de votre corps. La corrélation avec le sommeil montre l'impact des différentes quantités quotidiennes sur la durée de sommeil. La corrélation avec la fréquence cardiaque au repos (Pro) révèle si plus de café déplace votre référence cardiovasculaire.

### ⌚ Apple Watch et Siri
Complications "Caféine actuelle" et "Prévision de sommeil" sur tous les cadrans modernes. Touchez une complication pour enregistrer votre boisson par défaut en un seul écran. "Dis Siri, ajoute un café" fonctionne sans ouvrir l'app. Notifications de fenêtre cortisol au bon moment.

### 🤖 IA, 100 % sur l'appareil
Apple Intelligence génère des commentaires personnalisés sur votre caféine, adaptés à votre énergie, à l'heure et à vos rythmes de sommeil. Les fondations de recherche viennent du [projet JudgeGPT](https://github.com/aloth/JudgeGPT). Rien ne quitte votre appareil.

### 🔒 Intégration Apple et confidentialité
HealthKit écrit la caféine dans Apple Santé et lit le sommeil et la fréquence cardiaque au repos. iCloud synchronise entre iPhone, iPad et Mac. Export CSV pour garder la pleine maîtrise de vos données. Tous les calculs et l'IA tournent en local : pas de compte, pas de serveur, pas de télémétrie.

## Fonctions Pro

| Fonction | Pro ? |
|---|---|
| Carnet et analytique d'extraction | Pro |
| Corrélation avec la fréquence cardiaque au repos | Pro |
| Insights IA (Apple Intelligence) | Pro |
| Personnalisation des widgets | Pro |
| HealthKit bidirectionnel et import/export CSV | Pro |
| Suivi caféine et cortisol, prédiction du sommeil, corrélation sommeil, widgets, complications Watch, Siri | Gratuit |

*Les Insights IA nécessitent un iPhone 15 Pro ou de la série 16, un iPad Air/Pro avec M1+, un iPad mini avec A17 Pro ou un Mac Apple Silicon, sous iOS 18.1+ / iPadOS 18.1+ / macOS 15.1+.*

## Captures

<table>
<tr>
<td width="50%">

### Caféine et cortisol en temps réel
La courbe d'élimination de la caféine accompagnée du rythme naturel du cortisol, avec des recommandations de timing personnalisées.

<img src="screenshots/mindful-coffee-caffeine-tracker-cortisol-rhythm-chart.png" alt="Mindful Coffee affichant la courbe de caféine et le rythme du cortisol" width="400"/>

</td>
<td width="50%">

### Body Insights
Visualisez la relation entre votre consommation de caféine, votre durée de sommeil et votre fréquence cardiaque au repos depuis Apple Santé.

<img src="screenshots/caffeine-sleep-correlation-analysis-ios-app.png" alt="Analyse de corrélation entre caféine et sommeil" width="400"/>

</td>
</tr>
<tr>
<td width="50%">

### Saisie rapide avec prédictions intelligentes
Enregistrez café, thé ou boisson énergisante en un instant. Voyez en temps réel l'impact prévu sur votre sommeil.

<img src="screenshots/coffee-tea-caffeine-logging-interface-smart-predictions.png" alt="Interface de saisie rapide de caféine" width="400"/>

</td>
<td width="50%">

### Calibrage personnel du métabolisme
Réglez la sensibilité, la demi-vie, les seuils de sommeil et les paramètres de cortisol pour un suivi adapté à votre corps.

<img src="screenshots/cortisol-rhythm-settings-personal-metabolism-assistant.png" alt="Assistant personnel de métabolisme et réglages du rythme du cortisol" width="400"/>

</td>
</tr>
</table>

## La confidentialité d'abord

Vos données restent sur votre appareil ou se synchronisent en toute sécurité via votre iCloud personnel. Toutes les données de consommation sont stockées localement avec SwiftData, l'accès à HealthKit nécessite votre autorisation explicite, et **tous les calculs, analyses et Insights IA s'exécutent intégralement sur l'appareil** : rien n'est jamais envoyé à un serveur.

Consultez la [politique de confidentialité complète](https://github.com/aloth/mindful-coffee/blob/main/privacy_policy.md).

## Ressources

- 📖 [**FAQ**](./FAQ_fr.md) — science de la caféine, fonctions de l'app, dépannage · également en [English](./FAQ.md) · [Deutsch](./FAQ_de.md) · [Español](./FAQ_es.md) · [日本語](./FAQ_ja.md) · [简体中文](./FAQ_zh-Hans.md)
- 🔬 [**Bases scientifiques**](./RESEARCH_BACKGROUND.md) — la science derrière le modèle de cortisol
- 🌍 **Langues** — entièrement localisée en anglais, allemand, espagnol, français, japonais et chinois simplifié
- 🌐 [**Site officiel**](http://mindfulcoffee.alexloth.com)
- 🧘 **Apps liées** — [Mindful Body](https://github.com/aloth/mindful-body) · [Trackless Links](https://github.com/aloth/trackless-links)

## Collaboration de recherche

Vous êtes chercheur ou étudiant en chronobiologie, science du sommeil ou domaine connexe ? Écrivez à `support+mindfulcoffee@alexloth.com`.

## Retours

- 🐛 [Signaler un bug](https://github.com/aloth/mindful-coffee/issues/new?template=bug_report.md)
- 💡 [Proposer une fonctionnalité](https://github.com/aloth/mindful-coffee/issues/new?template=feature_request.md)

[![Télécharger sur l'App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/fr/app/mindful-coffee-tracks-caffeine/id6742878005?platform=iphone)
