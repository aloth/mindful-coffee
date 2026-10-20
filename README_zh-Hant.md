🇺🇸 [English](README.md) | 🇩🇪 [Deutsch](README_de.md) | 🇪🇸 [Español](README_es.md) | 🇫🇷 [Français](README_fr.md) | 🇮🇹 [Italiano](README_it.md) | 🇧🇷 [Português](README_pt-BR.md) | 🇳🇱 [Nederlands](README_nl.md) | 🇸🇪 [Svenska](README_sv.md) | 🇯🇵 [日本語](README_ja.md) | 🇰🇷 [한국어](README_ko.md) | 🇨🇳 [简体中文](README_zh-Hans.md) | 🇹🇼 **繁體中文**

# Mindful Coffee - 適用於 iPhone、iPad 與 Mac 的咖啡因追蹤器與沖煮日誌

[![App Store](https://img.shields.io/badge/App_Store-下載-blue?logo=apple&logoColor=white)](https://apps.apple.com/tw/app/mindful-coffee-tracks-caffeine/id6742878005)
[![Swift](https://img.shields.io/badge/Swift-6.0-orange?logo=swift&logoColor=white)](https://swift.org)
[![平台](https://img.shields.io/badge/平台-iOS_17+-lightgrey?logo=apple)](https://developer.apple.com/ios/)
[![GitHub stars](https://img.shields.io/github/stars/aloth/mindful-coffee?style=social)](https://github.com/aloth/mindful-coffee/stargazers)

<p align="center">
  <img src="assets/images/mindful-coffee-caffeine-tracker-sleep-optimization-hero.png" alt="Mindful Coffee：智慧咖啡因追蹤，結合睡眠預測與皮質醇節律最佳化" width="700">
</p>

**沖得更好。睡得更聰明。**

Mindful Coffee 是唯一一款將完整的**沖煮日誌**、個人代謝咖啡因模型與裝置端睡眠預測結合在一起的 iOS App。記錄每一杯濃縮咖啡、V60、AeroPress、Chemex、冷萃、抹茶或茶，精準掌握咖啡因何時會從體內代謝完畢，並了解身體自然的皮質醇節律。採用 Apple 的 **Liquid Glass** 設計語言打造，是 **Mindful Apps** 系列的一員，與 [Mindful Body](https://github.com/aloth/mindful-body) 並列。

[![在 App Store 下載](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/tw/app/mindful-coffee-tracks-caffeine/id6742878005?platform=iphone)

## 重點特色

### ☕ 沖煮日誌
濃縮咖啡、V60、AeroPress、Chemex、法壓壺、摩卡壺、冷萃，還有茶、抹茶與功夫茶。研磨粗細、劑量、比例、時間、溫度與評分，在一個優雅的流程中全部記下。內建配方、幫你更快調整到位的智慧建議，以及協助你找出最佳一杯的沖煮分析。

### 🧬 皮質醇與咖啡因模型
個人化的半衰期模型會預測咖啡因何時從體內代謝完畢，以及身體何時準備好入睡。皮質醇節律檢視會呈現你天然的能量曲線，讓你把咖啡安排在真正有幫助的時段。你平常的起床時間會根據「健康」App 的睡眠資料自動推算：取最多 14 個夜晚的中位數，而不是單一一個早晨，因此不需任何設定，時機建議就能貼合你真實的作息節律。

### ❤️ Body Insights（來自「健康」App）
將你的咖啡因攝取量與身體的實際反應交叉比對。睡眠關聯會顯示不同每日攝取量對睡眠時長的影響。靜止心率關聯（Pro）則會揭示多喝咖啡是否會推高你的心血管基準值。

### ⌚ Apple Watch 與 Siri
所有新款錶面都能使用「目前咖啡因」與「就寢預測」複雜功能。點一下複雜功能，就能在單一畫面中記錄你的預設飲品。「嘿 Siri, log a coffee」不必開啟 App 也能使用。皮質醇時段提醒會在恰當的時刻提醒你。

### 🤖 AI 洞察，完全在裝置端執行
Apple Intelligence 會產生個人化的咖啡因評論，並依你的精力狀態、一天中的時段與睡眠模式調整內容。AI 研究基礎來自 [JudgeGPT 專案](https://github.com/aloth/JudgeGPT)。任何資料都不會離開你的裝置。

### 🔒 Apple 整合與隱私
HealthKit 同步會將咖啡因寫入「健康」App，並讀取睡眠與靜止心率資料。iCloud 可在 iPhone、iPad 與 Mac 之間同步。CSV 匯出讓你完全擁有自己的資料。所有運算與 AI 都在本機執行：沒有帳號、沒有伺服器、沒有遙測。

## Pro 功能

| 功能 | 是否為 Pro？ |
|---|---|
| 沖煮日誌與沖煮分析 | Pro |
| 靜止心率關聯分析 | Pro |
| AI 洞察（Apple Intelligence） | Pro |
| 小工具自訂 | Pro |
| HealthKit 雙向同步與 CSV 匯入/匯出 | Pro |
| 咖啡因與皮質醇追蹤、睡眠預測、睡眠關聯、小工具、Apple Watch 複雜功能、Siri | 免費 |

*AI 洞察需要 iPhone 15 Pro 或 16 系列、搭載 M1 以上晶片的 iPad Air/Pro、搭載 A17 Pro 的 iPad mini，或搭載 Apple 晶片的 Mac，並執行 iOS 18.1+ / iPadOS 18.1+ / macOS 15.1+。*

## 螢幕截圖

<table>
<tr>
<td width="50%">

### 即時追蹤咖啡因與皮質醇
咖啡因衰減曲線與身體天然的皮質醇節律並列呈現，並提供個人化的時機建議。

<img src="screenshots/mindful-coffee-caffeine-tracker-cortisol-rhythm-chart.png" alt="Mindful Coffee App 顯示即時咖啡因衰減圖表、皮質醇節律曲線與睡眠預測" width="400"/>

</td>
<td width="50%">

### Body Insights
查看咖啡因攝取量與「健康」App 中睡眠時長及靜止心率之間的關聯。

<img src="screenshots/caffeine-sleep-correlation-analysis-ios-app.png" alt="咖啡因與睡眠關聯分析，顯示不同咖啡因攝取量下的平均睡眠時長" width="400"/>

</td>
</tr>
<tr>
<td width="50%">

### 快速記錄與智慧預測
立即記錄咖啡、茶或能量飲料。即時查看每一杯飲品將如何影響你的睡眠。

<img src="screenshots/coffee-tea-caffeine-logging-interface-smart-predictions.png" alt="快速記錄咖啡因的介面，包含飲品圖示、咖啡因含量與睡眠影響智慧預測" width="400"/>

</td>
<td width="50%">

### 個人代謝校準
調整敏感度、半衰期、睡眠閾值與皮質醇參數，讓追蹤結果符合你的身體。

<img src="screenshots/cortisol-rhythm-settings-personal-metabolism-assistant.png" alt="個人代謝助理與皮質醇節律自訂設定，實現精準的咖啡因追蹤" width="400"/>

</td>
</tr>
</table>

## 隱私優先

你的資料會留在你的裝置上，或透過你個人的 iCloud 安全同步。所有攝取資料都以 SwiftData 儲存在本機，存取 HealthKit 需要你明確授權，而且**所有運算、分析與 AI 洞察都完全在裝置端執行**，不會有任何資料傳送到伺服器。

閱讀完整的[隱私權政策](https://github.com/aloth/mindful-coffee/blob/main/privacy_policy.md)。

## 資源

- 📖 [**FAQ**](./FAQ_zh-Hant.md) - 咖啡因科學、App 功能、疑難排解 · 其他語言版本：[English](./FAQ.md) · [Deutsch](./FAQ_de.md) · [Español](./FAQ_es.md) · [Français](./FAQ_fr.md) · [Italiano](./FAQ_it.md) · [Português](./FAQ_pt-BR.md) · [Nederlands](./FAQ_nl.md) · [Svenska](./FAQ_sv.md) · [日本語](./FAQ_ja.md) · [한국어](./FAQ_ko.md) · [简体中文](./FAQ_zh-Hans.md)
- 🔬 [**研究背景**](./RESEARCH_BACKGROUND.md) - 皮質醇模型背後的科學
- 🌍 **語言** - 完整在地化支援英文、德文、西班牙文、法文、義大利文、葡萄牙文（巴西）、荷蘭文、瑞典文、日文、韓文、簡體中文與繁體中文
- 🌐 [**官方網站**](http://mindfulcoffee.alexloth.com)
- 🧘 **相關 App** - [Mindful Body](https://github.com/aloth/mindful-body) · [Trackless Links](https://github.com/aloth/trackless-links)

## 研究合作

如果你是時間生物學、睡眠科學或相關領域的研究人員或學生，歡迎寫信至 `support@alexloth.com` 與我們聯絡。

## 意見回饋

- 🐛 [回報錯誤](https://github.com/aloth/mindful-coffee/issues/new?template=bug_report.md)
- 💡 [建議新功能](https://github.com/aloth/mindful-coffee/issues/new?template=feature_request.md)

[![在 App Store 下載](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/tw/app/mindful-coffee-tracks-caffeine/id6742878005?platform=iphone)
