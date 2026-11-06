<div align="center">

<img src="assets/header.svg" alt="KasayaBaobei, mobile and full-stack engineer at Mojiya Studio" width="854" height="260" />

[![Mojiya](https://img.shields.io/badge/mojiya.app-site-0d1117?style=flat-square&logo=cloudflare&logoColor=f38020)](https://mojiya.app)
[![Features](https://img.shields.io/badge/mojiya.app-features-0d1117?style=flat-square&logo=readme&logoColor=f4a261)](https://mojiya.app/features)
[![Email](https://img.shields.io/badge/support-mojiya.app-0d1117?style=flat-square&logo=minutemailer&logoColor=ea4335)](mailto:support@mojiya.app)

</div>

```console
$ cat about.txt
```

I build Mojiya, a Japanese study app for Android, iOS, the web and the browser, from one Kotlin Multiplatform codebase.

- **Ship.** Solo-built, from the content pipeline to the store listings, on Android, iOS and the web, plus four browser extension stores.
- **Measure.** Study pacing comes from simulating a year of real FSRS reviews, not from guessing.
- **Build.** Content pipelines, sync backends, OCR and audio, end to end.

```console
$ ls projects/
```

| Project | What it does | Stack |
|---|---|---|
| [**Mojiya**](https://mojiya.app) | Kanji, vocabulary, grammar and kana courses with a dictionary, EPUB reader and subtitle player. The same features on every platform. | Kotlin · Compose Multiplatform · SQLite |
| [**Mojiya extension**](https://mojiya.app/features#extension) | Pop-up dictionary and subtitle mining on any page, with Anki export. Chrome, Edge, Firefox and Safari. | TypeScript · Kotlin/JS |
| **Sync relay** | Event-sourced progress sync across devices on an append-only log. | Kotlin · Ktor · PostgreSQL |
| **Content pipeline** | Eleven stages from JMdict, KANJIDIC2, KanjiVG, Tatoeba and Kanjium to a byte-reproducible database with 35,000+ voiced clips. | Python · SQLite · Amazon Polly |

All four are private. Mojiya ships through the Play Store, the App Store and [mojiya.app](https://mojiya.app).

```console
$ cat skills.txt
```

**Mobile**

<img src="https://img.shields.io/badge/Android-161b22?style=for-the-badge&logo=android&logoColor=3ddc84" alt="Android" /> <img src="https://img.shields.io/badge/iOS-161b22?style=for-the-badge&logo=apple&logoColor=white" alt="iOS" /> <img src="https://img.shields.io/badge/Compose%20Multiplatform-161b22?style=for-the-badge&logo=jetpackcompose&logoColor=4285f4" alt="Compose Multiplatform" /> <img src="https://img.shields.io/badge/Kotlin%20Multiplatform-161b22?style=for-the-badge&logo=kotlin&logoColor=7f52ff" alt="Kotlin Multiplatform" />

**Domain**

<img src="https://img.shields.io/badge/Spaced%20repetition%20(FSRS)-161b22?style=for-the-badge" alt="Spaced repetition (FSRS)" /> <img src="https://img.shields.io/badge/JMdict%20%C2%B7%20KANJIDIC2%20%C2%B7%20KanjiVG-161b22?style=for-the-badge" alt="JMdict, KANJIDIC2, KanjiVG" /> <img src="https://img.shields.io/badge/Japanese%20text%20segmentation-161b22?style=for-the-badge" alt="Japanese text segmentation" />

**Stack**
<img src="https://skillicons.dev/icons?i=kotlin,swift,ts,python,sqlite,postgres&theme=dark" alt="Kotlin, Swift, TypeScript, Python, SQLite, PostgreSQL" height="36" />

**Runs on**
<img src="https://skillicons.dev/icons?i=androidstudio,gradle,cloudflare,aws&theme=dark" alt="Android Studio, Gradle, Cloudflare, AWS" height="36" />
