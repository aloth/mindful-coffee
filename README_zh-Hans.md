🇺🇸 [English](README.md) | 🇩🇪 [Deutsch](README_de.md) | 🇪🇸 [Español](README_es.md) | 🇫🇷 [Français](README_fr.md) | 🇯🇵 [日本語](README_ja.md) | 🇨🇳 **中文**

# Mindful Coffee — 适用于 iPhone、iPad 和 Mac 的咖啡因追踪 & 冲煮日志

[![App Store](https://img.shields.io/badge/App_Store-下载-blue?logo=apple&logoColor=white)](https://apps.apple.com/cn/app/mindful-coffee-tracks-caffeine/id6742878005)
[![Swift](https://img.shields.io/badge/Swift-6.0-orange?logo=swift&logoColor=white)](https://swift.org)
[![平台](https://img.shields.io/badge/平台-iOS_17+-lightgrey?logo=apple)](https://developer.apple.com/ios/)
[![GitHub stars](https://img.shields.io/github/stars/aloth/mindful-coffee?style=social)](https://github.com/aloth/mindful-coffee/stargazers)

<p align="center">
  <img src="assets/images/mindful-coffee-caffeine-tracker-sleep-optimization-hero.png" alt="Mindful Coffee — 智能咖啡因追踪，配合睡眠预测与皮质醇节律优化" width="700">
</p>

**冲得更好。睡得更香。**

Mindful Coffee 是唯一一款将完整的**冲煮日志**与个人化咖啡因代谢模型相结合，并在设备本地完成睡眠预测的 iOS 应用。无论 Espresso、V60、爱乐压、Chemex、冷萃、抹茶还是茶，每一杯都能记录，让你清楚知道咖啡因何时排出体外，并理解身体自然的皮质醇节律。采用 Apple **Liquid Glass** 设计语言打造，是 **Mindful Apps** 系列的一员，与 [Mindful Body](https://github.com/aloth/mindful-body) 并列。

[![从 App Store 下载](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/cn/app/mindful-coffee-tracks-caffeine/id6742878005?platform=iphone)

## 亮点

### ☕ 冲煮日志
Espresso、V60、爱乐压、Chemex、法压、摩卡壶、冷萃，以及茶、抹茶、工夫茶。研磨度、粉量、比例、时间、温度、评分，全部在一个流畅的界面中记录。内置配方，结合过往数据的智能建议帮你更快调试，再用分析功能找出最佳一杯。

### 🧬 皮质醇 × 咖啡因模型
基于个人化的半衰期模型，预测咖啡因何时排出体外、身体何时准备好入睡。皮质醇节律视图展示你天然的能量曲线，让你把咖啡安排在真正有效的时间窗口。

### ❤️ 来自「健康」的 Body Insights
将咖啡因摄入与身体的真实反应交叉对照。睡眠相关性显示不同每日摄入量对睡眠时长的影响，静息心率相关性（Pro）则告诉你更多咖啡是否真的会推高心血管基线。

### ⌚ Apple Watch 与 Siri
所有现代表盘都可显示「当前咖啡因」和「就寝预测」复杂功能。点击复杂功能即可一屏内记录默认饮品。无需打开应用，「嘿 Siri，记一杯咖啡」即可记录。皮质醇时段提醒会在合适的时刻提示你。

### 🤖 完全本地的 AI 洞察
Apple Intelligence 提供个性化的咖啡因点评，根据你的精力水平、时段与睡眠模式自动调整。AI 研究基础来自 [JudgeGPT 项目](https://github.com/aloth/JudgeGPT)。所有数据都不会离开你的设备。

### 🔒 Apple 生态整合与隐私
HealthKit 将咖啡因写入「健康」应用，并读取睡眠和静息心率数据。iCloud 在 iPhone、iPad 与 Mac 之间同步。CSV 导出让数据完全归你所有。所有计算与 AI 都在本地运行 — 不需要账号，不连服务器，没有遥测。

## Pro 功能

| 功能 | 是否 Pro? |
|---|---|
| 冲煮日志与冲煮分析 | Pro |
| 静息心率相关性分析 | Pro |
| AI 洞察（Apple Intelligence） | Pro |
| 小组件自定义 | Pro |
| HealthKit 双向同步与 CSV 导入/导出 | Pro |
| 咖啡因与皮质醇追踪、睡眠预测、睡眠相关性、小组件、Watch 复杂功能、Siri | 免费 |

*AI 洞察需要 iPhone 15 Pro 或 16 系列、搭载 M1 及以上的 iPad Air/Pro、搭载 A17 Pro 的 iPad mini，或 Apple Silicon Mac，运行 iOS 18.1+ / iPadOS 18.1+ / macOS 15.1+。*

## 截图

<table>
<tr>
<td width="50%">

### 实时咖啡因 × 皮质醇
咖啡因衰减曲线与身体自然皮质醇节律并排呈现，配合个性化的时间建议。

<img src="screenshots/mindful-coffee-caffeine-tracker-cortisol-rhythm-chart.png" alt="Mindful Coffee 实时咖啡因衰减曲线与皮质醇节律及睡眠预测" width="400"/>

</td>
<td width="50%">

### Body Insights
查看咖啡因摄入与「健康」中的睡眠时长和静息心率之间的关联。

<img src="screenshots/caffeine-sleep-correlation-analysis-ios-app.png" alt="咖啡因与睡眠相关性分析" width="400"/>

</td>
</tr>
<tr>
<td width="50%">

### 智能预测的快速记录
快速记录咖啡、茶或能量饮料。每一杯都能实时看到对睡眠的影响预测。

<img src="screenshots/coffee-tea-caffeine-logging-interface-smart-predictions.png" alt="带饮品图标和智能睡眠预测的快速记录界面" width="400"/>

</td>
<td width="50%">

### 个性化代谢校准
调节敏感度、半衰期、睡眠阈值和皮质醇参数，让追踪贴合你的身体。

<img src="screenshots/cortisol-rhythm-settings-personal-metabolism-assistant.png" alt="个人代谢助手与皮质醇节律设置" width="400"/>

</td>
</tr>
</table>

## 隐私优先

你的数据始终留在设备上，或通过你的个人 iCloud 安全同步。所有摄入数据都通过 SwiftData 本地存储，HealthKit 访问需要你明确授权，**所有计算、分析与 AI 洞察都完全在设备上运行** — 任何数据都不会发送到服务器。

阅读完整的[隐私政策](https://github.com/aloth/mindful-coffee/blob/main/privacy_policy.md)。

## 资源

- 📖 [**常见问题**](./FAQ_zh-Hans.md) — 咖啡因科学、应用功能、问题排查 · 也有 [English](./FAQ.md) · [Deutsch](./FAQ_de.md) · [Español](./FAQ_es.md) · [Français](./FAQ_fr.md) · [日本語](./FAQ_ja.md)
- 🔬 [**研究背景**](./RESEARCH_BACKGROUND.md) — 皮质醇模型背后的科学
- 🌍 **支持语言** — 完整本地化为英语、德语、西班牙语、法语、日语和简体中文
- 🌐 [**官方网站**](http://mindfulcoffee.alexloth.com)
- 🧘 **相关应用** — [Mindful Body](https://github.com/aloth/mindful-body) · [Trackless Links](https://github.com/aloth/trackless-links)

## 研究合作

如果你是从事时间生物学、睡眠科学或相关领域的研究者或学生，欢迎邮件至 `support+mindfulcoffee@alexloth.com`。

## 反馈

- 🐛 [报告错误](https://github.com/aloth/mindful-coffee/issues/new?template=bug_report.md)
- 💡 [建议功能](https://github.com/aloth/mindful-coffee/issues/new?template=feature_request.md)

[![从 App Store 下载](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/cn/app/mindful-coffee-tracks-caffeine/id6742878005?platform=iphone)
