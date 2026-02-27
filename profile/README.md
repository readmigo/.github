<h1 align="center">Readmigo</h1>

<p align="center">
  <strong>AI-Powered English Reading Companion</strong>
</p>

<p align="center">
  Readmigo helps language learners improve their English through immersive reading experiences with AI-assisted comprehension tools.<br>
  Access <strong>100,000+ classic books</strong> and <strong>20,000+ audiobooks</strong> — all free.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/repos-35%2B-0969DA?style=flat-square" alt="repos">
  <img src="https://img.shields.io/badge/languages-10%2B-2da44e?style=flat-square" alt="languages">
  <img src="https://img.shields.io/badge/platforms-iOS%20%7C%20Android%20%7C%20Web-6e40c9?style=flat-square" alt="platforms">
  <img src="https://img.shields.io/badge/books-100%2C000%2B-f97316?style=flat-square" alt="books">
  <img src="https://img.shields.io/badge/audiobooks-20%2C000%2B-ec4899?style=flat-square" alt="audiobooks">
  <img src="https://img.shields.io/badge/UI_languages-11-14b8a6?style=flat-square" alt="ui languages">
</p>

---

## Get Readmigo

<p align="center">
  <a href="https://readmigo.app">
    <img src="https://img.shields.io/badge/Official_Website-readmigo.app-0969DA?style=for-the-badge&logo=safari&logoColor=white" height="44" alt="Official Website">
  </a>
</p>

<p align="center">
  <a href="https://apps.apple.com/us/app/readmigo/id6756987013">
    <img src="https://raw.githubusercontent.com/readmigo/.github/main/profile/assets/app-store-badge.svg" height="44" alt="Download on App Store">
  </a>
  &nbsp;&nbsp;
  <a href="https://play.google.com/store/apps/details?id=com.readmigo.app">
    <img src="https://raw.githubusercontent.com/readmigo/.github/main/profile/assets/google-play-badge.png" height="44" alt="Get it on Google Play">
  </a>
  &nbsp;&nbsp;
  <a href="https://web.readmigo.app">
    <img src="https://img.shields.io/badge/Open_Web_App-4A90D9?style=for-the-badge&logo=googlechrome&logoColor=white" height="44" alt="Open Web App">
  </a>
</p>

---

## Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/readmigo/.github/main/profile/assets/57.png" width="200" alt="Library">
  <img src="https://raw.githubusercontent.com/readmigo/.github/main/profile/assets/58.png" width="200" alt="Reader">
  <img src="https://raw.githubusercontent.com/readmigo/.github/main/profile/assets/59.png" width="200" alt="AI Assistant">
  <img src="https://raw.githubusercontent.com/readmigo/.github/main/profile/assets/60.png" width="200" alt="Reading">
</p>

## Features

- **100,000+ Books** — Massive collection from Project Gutenberg, including classics from Shakespeare to Jane Austen
- **20,000+ Audiobooks** — Free audiobooks from LibriVox, read by real narrators
- **AI Reading Assistant** — Contextual word explanations, sentence simplification, and paragraph translations
- **TTS Read Aloud** — Listen to any book with natural AI voices
- **Custom Typesetting Engine** — Native C++ rendering engine for pixel-perfect ebook layout across all platforms
- **PDF Support** — AI-powered PDF classification and rendering: ebooks, papers, magazines, comics, textbooks
- **Multi-Platform** — Available on iOS, Android, Flutter (Web/Mobile), and Next.js Web
- **11 Languages** — Interface localized for learners worldwide

## Our Repositories

### Client Apps

| Repository | Description | Language |
|------------|-------------|----------|
| [ios](https://github.com/readmigo/ios) | Native iOS app (Swift/SwiftUI) | Swift |
| [android](https://github.com/readmigo/android) | Native Android app (Kotlin/Jetpack Compose) | Kotlin |
| [flutter](https://github.com/readmigo/flutter) | Cross-platform Flutter app with native C++ typesetting engine | Dart |
| [web](https://github.com/readmigo/web) | Web reader app built with Next.js | TypeScript |
| [mobile](https://github.com/readmigo/mobile) | Cross-platform mobile app (React Native/Expo) | TypeScript |

### Backend & Services

| Repository | Description | Language |
|------------|-------------|----------|
| [api](https://github.com/readmigo/api) | Backend API (NestJS + Prisma) | TypeScript |
| [nlp](https://github.com/readmigo/nlp) | Natural Language Processing service | Python |
| [reader-engine](https://github.com/readmigo/reader-engine) | Core reading engine for ebook parsing and rendering | TypeScript |

### Typesetting Engine Ecosystem

A custom C++ typesetting engine that delivers pixel-perfect ebook rendering on every platform.

| Repository | Description | Language |
|------------|-------------|----------|
| [typesetting](https://github.com/readmigo/typesetting) | Cross-platform C++ typesetting engine — Standard Ebooks CSS, EPUB rendering | C++ |
| [typesetting-core](https://github.com/readmigo/typesetting-core) | Fast C++ text layout engine — block flow, line breaking, pagination | C++ |
| [typesetting-css](https://github.com/readmigo/typesetting-css) | Lightweight CSS parser — tokenizer, cascade, computed styles | C++ |
| [typesetting-html](https://github.com/readmigo/typesetting-html) | HTML to structured ContentBlock flow — DOM parsing engine | C++ |
| [typesetting-interaction](https://github.com/readmigo/typesetting-interaction) | Hit testing and text queries — highlighting, TTS, translation support | C++ |

### Document Processing Pipeline

AI-powered pipeline for handling every PDF and document type.

| Repository | Description | Language |
|------------|-------------|----------|
| [pdf-classifier](https://github.com/readmigo/pdf-classifier) | Automatic PDF content type classifier — ebook, paper, magazine, comic, textbook, scanned | Python |
| [pdf2epub](https://github.com/readmigo/pdf2epub) | Convert ebook-style PDF to EPUB — text reflow, chapter splitting | Python |
| [pdfreader](https://github.com/readmigo/pdfreader) | PDF page image renderer — fallback rendering for any PDF type | Python |
| [pdf-ocr](https://github.com/readmigo/pdf-ocr) | OCR preprocessing for scanned PDFs — deskew, denoise, binarize, Tesseract | Python |
| [ocr-pipeline](https://github.com/readmigo/ocr-pipeline) | End-to-end OCR processing pipeline | Python |
| [comic-renderer](https://github.com/readmigo/comic-renderer) | Comic/manga page renderer with panel detection — RTL and LTR support | Python |
| [magazine-renderer](https://github.com/readmigo/magazine-renderer) | Magazine/newspaper layout renderer with text region detection | Python |
| [textbook-reflower](https://github.com/readmigo/textbook-reflower) | Textbook hybrid reflow engine — text reflow with diagram/sidebar preservation | Python |
| [paper-typesetting](https://github.com/readmigo/paper-typesetting) | Academic paper layout engine — dual-column, formula, citation, figure/table extraction | Python |

### Format Parsers

| Repository | Description | Language |
|------------|-------------|----------|
| [epubreader](https://github.com/readmigo/epubreader) | EPUB parser and content extractor — EPUB2/3 with ZIP, OPF, NCX, NAV parsing | C++ |
| [mobireader](https://github.com/readmigo/mobireader) | MOBI/AZW3 parser — PDB, PalmDOC, KF8 format support | C++ |
| [gutenberg](https://github.com/readmigo/gutenberg) | Project Gutenberg content processing and catalog pipeline | TypeScript |

### Tools & Internal

| Repository | Description | Language |
|------------|-------------|----------|
| [dashboard](https://github.com/readmigo/dashboard) | Admin dashboard (React Admin + Vite) | TypeScript |
| [content-studio](https://github.com/readmigo/content-studio) | Content editing and proofreading tool | TypeScript |
| [voxclone](https://github.com/readmigo/voxclone) | AI Voice Cloning — personalized messages in 18+ dialects and languages | Swift |
| [shipkit](https://github.com/readmigo/shipkit) | AI Agent-friendly unified app publishing MCP Server | TypeScript |

### Web Properties

| Repository | Description | Language |
|------------|-------------|----------|
| [website](https://github.com/readmigo/website) | Marketing website (readmigo.app) | HTML |
| [ai](https://github.com/readmigo/ai) | AI Tech Review — Web Frontend | TypeScript |
| [blog](https://github.com/readmigo/blog) | Official Readmigo blog (Hugo + PaperMod) | HTML |

## Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Backend** | NestJS, Prisma, PostgreSQL, Redis |
| **Web** | Next.js, React, TypeScript, Tailwind CSS |
| **iOS** | Swift, SwiftUI |
| **Android** | Kotlin, Jetpack Compose |
| **Cross-Platform** | Flutter (Dart), React Native, Expo |
| **AI / LLM** | OpenAI, Anthropic Claude, Deepseek |
| **Audio** | FFmpeg, Azure Speech, ElevenLabs, OpenAI TTS |
| **NLP** | Python, spaCy |
| **Typesetting** | C++17, Standard Ebooks CSS, HarfBuzz, FreeType |
| **Document AI** | Python, Tesseract, OpenCV, PyMuPDF |
| **Infrastructure** | Fly.io, Vercel, Cloudflare Pages, Cloudflare R2, Neon DB |

## Contact

- Website: [readmigo.app](https://readmigo.app)
- Email: [support@readmigo.app](mailto:support@readmigo.app)
- GitHub: [github.com/readmigo](https://github.com/readmigo)
