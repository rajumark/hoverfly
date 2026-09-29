<div align="center">

# 🪰 Hoverfly

**On-device AI for Kotlin Multiplatform. Skip the server.**

Tiny Kotlin Multiplatform models that run inside your app on Android, iOS, macOS, JVM desktop, JavaScript and WebAssembly: offline, private, and fast.

[![Website](https://img.shields.io/badge/website-rajumark.github.io%2Fhoverfly-d7ff4e?style=flat-square&labelColor=15140f)](https://rajumark.github.io/hoverfly)
![Models](https://img.shields.io/badge/models-8-d7ff4e?style=flat-square&labelColor=15140f)
![Size](https://img.shields.io/badge/size-2--9%20MB-d7ff4e?style=flat-square&labelColor=15140f)
![Network](https://img.shields.io/badge/network%20calls-0-d7ff4e?style=flat-square&labelColor=15140f)
![Platforms](https://img.shields.io/badge/platforms-Android%20·%20iOS%20·%20desktop%20·%20web-d7ff4e?style=flat-square&labelColor=15140f)

</div>

## The models

| | Model | Does | Size | Headline result |
|---|---|---|---|---|
| 😀 | [**Moji**](https://rajumark.github.io/moji/) | Emoji suggestions | ~5 MB | 22+ languages |
| 🌐 | [**Beacon**](https://rajumark.github.io/beacon/) | Language detection | 8.5 MB | **88.3%** on chat · ML Kit 71.3% |
| ✍️ | [**Comma**](https://rajumark.github.io/comma/) | Punctuation restoration | 7.8 MB | **0.83 F1** on Hinglish · XLM-R (1.1 GB) 0.49 |
| 💬 | [**Comeback**](https://rajumark.github.io/comeback/) | Smart replies | 4.6 MB | **63.6%** good reply in top 3 |
| 🛡️ | [**Gatekeeper**](https://rajumark.github.io/gatekeeper/) | Toxicity detection | 3.8 MB | **98.8%** of everyday chat passes clean |
| 🙈 | [**Hideout**](https://rajumark.github.io/hideout/) | Personal-info hiding | 8 MB | **96%** Indian PII hidden · Presidio 64% |
| 🎨 | [**Chalk**](https://rajumark.github.io/chalk/) | Doodle recognition | 1.8 MB | **81%** first guess, 345 things |
| 😊 | [**Emotion**](https://rajumark.github.io/emotion/) | Emotion detection | 6.4 MB | **38%** top emotion on fresh chat · RoBERTa (499 MB) 36% |

## Three lines

```kotlin
// build.gradle.kts: commonMain (Maven Central)
implementation("io.github.rajumark:moji:2.0.0")

// anywhere in your app: Android, iOS, macOS, JVM desktop, JS or Wasm
Moji().use { moji ->
    moji.suggestions("Pay my bills")   // 💰 💸 🧾
}
```

## Why on-device

| | Cloud AI API | Hoverfly |
|---|:---:|:---:|
| Works offline | ❌ | ✅ |
| Text stays on the device | ❌ | ✅ |
| No server, no per-call bill | ❌ | ✅ |
| Size vs best open alternative | — | up to **193× smaller** |

## License

Free for products with up to **10,000 monthly active devices** per platform under the Hoverfly Community License.
Need more, or a model of your own? [Get in touch](mailto:raju348636@gmail.com?subject=Custom%20on-device%20model).
