🇺🇸 [English](README.md) | 🇩🇪 [Deutsch](README_de.md) | 🇪🇸 **Español** | 🇫🇷 [Français](README_fr.md) | 🇯🇵 [日本語](README_ja.md) | 🇨🇳 [中文](README_zh-Hans.md)

# Mindful Coffee — Tracker de cafeína y diario de extracción para iPhone, iPad y Mac

[![App Store](https://img.shields.io/badge/App_Store-Descargar-blue?logo=apple&logoColor=white)](https://apps.apple.com/es/app/mindful-coffee-tracks-caffeine/id6742878005)
[![Swift](https://img.shields.io/badge/Swift-6.0-orange?logo=swift&logoColor=white)](https://swift.org)
[![Plataforma](https://img.shields.io/badge/Plataforma-iOS_17+-lightgrey?logo=apple)](https://developer.apple.com/ios/)
[![GitHub stars](https://img.shields.io/github/stars/aloth/mindful-coffee?style=social)](https://github.com/aloth/mindful-coffee/stargazers)

<p align="center">
  <img src="assets/images/mindful-coffee-caffeine-tracker-sleep-optimization-hero.png" alt="Mindful Coffee — seguimiento inteligente de cafeína con predicción de sueño y optimización del ritmo de cortisol" width="700">
</p>

**Prepara mejor. Duerme mejor.**

Mindful Coffee es la única app de iOS que une un **diario de extracción** completo con un modelo personal del metabolismo de la cafeína y predicción de sueño en el dispositivo. Registra cada espresso, V60, AeroPress, Chemex, cold brew, matcha o té, comprueba con exactitud cuándo se eliminará la cafeína de tu organismo y entiende el ritmo natural de cortisol de tu cuerpo. Construida con el lenguaje de diseño **Liquid Glass** de Apple. Forma parte de la familia **Mindful Apps**, junto a [Mindful Body](https://github.com/aloth/mindful-body).

[![Descargar en el App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/es/app/mindful-coffee-tracks-caffeine/id6742878005?platform=iphone)

## Lo destacado

### ☕ Diario de extracción
Espresso, V60, AeroPress, Chemex, prensa francesa, moka, cold brew, además de té, matcha y Gong Fu. Anota molienda, dosis, ratio, tiempo, temperatura y valoración en un flujo elegante. Recetas integradas, sugerencias inteligentes para afinar más rápido y analítica para encontrar tu mejor taza.

### 🧬 Modelo de cortisol y cafeína
Un modelo personal de vida media predice cuándo tu cuerpo eliminará la cafeína y cuándo estará listo para dormir. La vista del ritmo de cortisol muestra tu curva natural de energía para que tomes café en las ventanas en las que de verdad ayuda.

### ❤️ Body Insights desde Apple Health
Cruza tu consumo de cafeína con la respuesta real de tu cuerpo. La correlación de sueño muestra el impacto de distintas cantidades diarias en la duración del descanso. La correlación con la frecuencia cardíaca en reposo (Pro) revela si más café altera tu base cardiovascular.

### ⌚ Apple Watch y Siri
Complicaciones "Cafeína ahora" y "Pronóstico de sueño" en cualquier esfera moderna. Toca una complicación para registrar tu bebida predeterminada en una sola pantalla. "Oye Siri, registra un café" funciona sin abrir la app. Avisos de ventana de cortisol que llegan en el momento adecuado.

### 🤖 IA totalmente en el dispositivo
Apple Intelligence genera comentarios personalizados sobre tu cafeína que se adaptan a tu nivel de energía, hora del día y patrones de sueño. La base de investigación es el [proyecto JudgeGPT](https://github.com/aloth/JudgeGPT). Nada sale de tu dispositivo.

### 🔒 Integración con Apple y privacidad
HealthKit escribe la cafeína en Apple Health y lee los datos de sueño y de frecuencia cardíaca en reposo. iCloud sincroniza entre iPhone, iPad y Mac. Exportación a CSV para que tus datos sigan siendo tuyos. Todos los cálculos y la IA se ejecutan localmente: sin cuentas, sin servidores, sin telemetría.

## Funciones Pro

| Función | ¿Pro? |
|---|---|
| Diario y analítica de extracción | Pro |
| Correlación con frecuencia cardíaca en reposo | Pro |
| Insights con IA (Apple Intelligence) | Pro |
| Personalización de widgets | Pro |
| HealthKit bidireccional e import/export CSV | Pro |
| Seguimiento de cafeína y cortisol, predicción de sueño, correlación de sueño, widgets, complicaciones de Watch, Siri | Gratis |

*Los Insights con IA requieren iPhone 15 Pro o serie 16, iPad Air/Pro con M1+, iPad mini con A17 Pro o Mac con Apple Silicon, con iOS 18.1+ / iPadOS 18.1+ / macOS 15.1+.*

## Capturas

<table>
<tr>
<td width="50%">

### Cafeína y cortisol en tiempo real
La curva de eliminación de cafeína junto al ritmo natural de cortisol, con recomendaciones personalizadas de timing.

<img src="screenshots/mindful-coffee-caffeine-tracker-cortisol-rhythm-chart.png" alt="Mindful Coffee mostrando la curva de cafeína y el ritmo de cortisol con predicción de sueño" width="400"/>

</td>
<td width="50%">

### Body Insights
Comprueba cómo tu consumo de cafeína se correlaciona con la duración del sueño y la frecuencia cardíaca en reposo desde Apple Health.

<img src="screenshots/caffeine-sleep-correlation-analysis-ios-app.png" alt="Análisis de correlación entre cafeína y sueño" width="400"/>

</td>
</tr>
<tr>
<td width="50%">

### Registro rápido con predicciones inteligentes
Registra café, té o bebidas energéticas al instante. Comprueba en tiempo real cómo cada bebida afectará a tu sueño.

<img src="screenshots/coffee-tea-caffeine-logging-interface-smart-predictions.png" alt="Interfaz de registro rápido de cafeína" width="400"/>

</td>
<td width="50%">

### Calibración personal del metabolismo
Ajusta sensibilidad, vida media, umbrales de sueño y parámetros de cortisol para que el seguimiento se adapte a tu cuerpo.

<img src="screenshots/cortisol-rhythm-settings-personal-metabolism-assistant.png" alt="Asistente personal de metabolismo y ajustes del ritmo de cortisol" width="400"/>

</td>
</tr>
</table>

## Privacidad primero

Tus datos se quedan en tu dispositivo o se sincronizan de forma segura mediante tu iCloud personal. Todos los datos de consumo se almacenan localmente con SwiftData, el acceso a HealthKit requiere tu permiso explícito y **todos los cálculos, análisis e Insights con IA se ejecutan completamente en el dispositivo**: nada se envía nunca a un servidor.

Lee la [política de privacidad completa](https://github.com/aloth/mindful-coffee/blob/main/privacy_policy.md).

## Recursos

- 📖 [**FAQ**](./FAQ_es.md) — ciencia de la cafeína, funciones de la app, solución de problemas · también en [English](./FAQ.md) · [Deutsch](./FAQ_de.md) · [Français](./FAQ_fr.md) · [日本語](./FAQ_ja.md) · [简体中文](./FAQ_zh-Hans.md)
- 🔬 [**Base científica**](./RESEARCH_BACKGROUND.md) — la ciencia detrás del modelo de cortisol
- 🌍 **Idiomas** — totalmente localizada en inglés, alemán, español, francés, japonés y chino simplificado
- 🌐 [**Sitio oficial**](http://mindfulcoffee.alexloth.com)
- 🧘 **Relacionados** — [Mindful Body](https://github.com/aloth/mindful-body) · [Trackless Links](https://github.com/aloth/trackless-links)

## Colaboración en investigación

Si eres investigador o estudiante en cronobiología, ciencia del sueño o áreas afines, escribe a `support+mindfulcoffee@alexloth.com`.

## Feedback

- 🐛 [Reportar un error](https://github.com/aloth/mindful-coffee/issues/new?template=bug_report.md)
- 💡 [Sugerir una función](https://github.com/aloth/mindful-coffee/issues/new?template=feature_request.md)

[![Descargar en el App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/es/app/mindful-coffee-tracks-caffeine/id6742878005?platform=iphone)
