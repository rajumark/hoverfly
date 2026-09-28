<div align="center">

# 🪰 Hoverfly

**On-device AI for Android. Skip the server.**

Tiny Kotlin models that run inside the phone: offline, private, and fast.

[![Website](https://img.shields.io/badge/website-rajumark.github.io%2Fhoverfly-d7ff4e?style=flat-square&labelColor=15140f)](https://rajumark.github.io/hoverfly)
![Models](https://img.shields.io/badge/models-7-d7ff4e?style=flat-square&labelColor=15140f)
![Size](https://img.shields.io/badge/size-2--9%20MB-d7ff4e?style=flat-square&labelColor=15140f)
![Network](https://img.shields.io/badge/network%20calls-0-d7ff4e?style=flat-square&labelColor=15140f)
![minSdk](https://img.shields.io/badge/minSdk-21-d7ff4e?style=flat-square&labelColor=15140f)

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

## Three lines

```kotlin
// build.gradle.kts  (JitPack)
implementation("com.github.rajumark:moji:v1.1.0")

// anywhere in your app
Moji(context).use { moji ->
    moji.suggestions("Pay my bills")   // 💰 💸 🧾
}
```

## Why on-device

| | Cloud AI API | Hoverfly |
|---|:---:|:---:|
| Works offline | ❌ | ✅ |
| Text stays on the phone | ❌ | ✅ |
| No server, no per-call bill | ❌ | ✅ |
| Size vs best open alternative | — | up to **193× smaller** |

## License

Free for products with up to **10,000 monthly active devices** per platform under the Hoverfly Community License.
Need more, or a model of your own? [Get in touch](mailto:raju348636@gmail.com?subject=Custom%20on-device%20model).
