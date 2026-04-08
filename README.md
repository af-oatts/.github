# Air Force OATTS Organization

Welcome to the **Air Force OATTS** organization! Home of OATTS (Official AFOQT & TBAS Test-familiarization Software), a cutting-edge learning platform designed to aid test-takers in preparation for critical assessments.

---

## 🎯 About AF-OATTS

OATTS is a downloadable learning application built to support students and test-takers in concept familiarization for the AFOQT (Air Force Officer Qualifying Test) and TBAS (Test of Basic Aviation Skills). As an **offline LMS** (Learning Management System), it delivers SCORM-compliant content without requiring internet connectivity.

This organization serves dual purposes:
- **Educational**: Helping students prepare for crucial Air Force qualifications
- **Research**: Supporting the United States Air Force in developing improved placement and qualifying tests

---

## 📦 Projects

### [**OATTS** (`oatts`)](https://github.com/af-oatts/oatts)
The main application—a desktop learning platform built with Tauri, React, and TypeScript.

- **Purpose**: Full-featured offline LMS for AFOQT/TBAS preparation
- **Languages**: TypeScript (95.1%), Rust (4.8%)
- **Key Technologies**:
  - **Tauri**: Desktop application framework
  - **React**: UI framework
  - **SCORM**: Content delivery standard
  - **i18n**: Internationalization support
  - **Tanstack Router**: Client-side routing
  - **Material-UI**: Component library

[View Repository →](https://github.com/af-oatts/oatts)

---

### [**Website** (`af-oatts.github.io`)](https://github.com/af-oatts/af-oatts.github.io)
The official AF-OATTS web presence—a modern landing and download page.

- **Purpose**: Marketing site and distribution hub for OATTS downloads
- **Languages**: Astro (77.2%), TypeScript (22.5%), JavaScript (0.3%)
- **Key Technologies**:
  - **Astro**: Static site generation
  - **TypeScript**: Type-safe development

[View Website →](https://af-oatts.github.io)

[View Repository →](https://github.com/af-oatts/af-oatts.github.io)

---

### [**Content** (`content`)](https://github.com/af-oatts/content)
Curriculum and learning modules for OATTS.

- **Purpose**: Repository for test-prep content, lessons, quizzes, and SCORM packages
- **Usage**: Included via git submodule in the main OATTS application

[View Repository →](https://github.com/af-oatts/content)

---

### [**OATTS Installer** (`oatts-installer`)](https://github.com/af-oatts/oatts-installer)
macOS-specific installer utility for OATTS.

- **Purpose**: Bypasses macOS gatekeeper restrictions for unsigned DMG files
- **Languages**: TypeScript (66.6%), Rust (23.6%), CSS (8.1%), HTML (1.7%)
- **Platforms**: macOS

[View Repository →](https://github.com/af-oatts/oatts-installer)

---

### [**Keygen** (`keygen`)](https://github.com/af-oatts/keygen)
Cryptographic key generation and management utility.

- **Purpose**: Secure key generation for data encryption and export features
- **Usage**: Used internally by OATTS for AES-256-GCM encryption

[View Repository →](https://github.com/af-oatts/keygen)

---

## 🛠 Tech Stack Overview

| Technology | Primary Use | Repos |
|-----------|------------|-------|
| **TypeScript** | Frontend development, type safety | oatts, oatts-installer, website |
| **Rust** | Performance-critical operations | oatts, oatts-installer, keygen |
| **React** | UI framework | oatts |
| **Tauri** | Desktop app framework | oatts |
| **Astro** | Static site generation | website |
| **SCORM** | Content delivery standard | oatts, content |

---

## 🚀 Getting Started

### For Users
Visit [af-oatts.github.io](https://af-oatts.github.io) to download OATTS for your platform.

### For Developers

#### Clone and Setup
```bash
git clone https://github.com/af-oatts/oatts.git
cd oatts
git submodule update --init --recursive
```

#### Requirements
- Rust ([install](https://www.rust-lang.org/tools/install))
- pnpm (`npm install -g pnpm@latest`)

#### Development
```bash
pnpm tauri dev
```

#### Building
```bash
pnpm tauri build
```

*Note: macOS builds require additional configuration. See the [OATTS README](https://github.com/af-oatts/oatts) for platform-specific details.*

---

## 🔒 Security & Privacy

OATTS prioritizes user privacy and data security:

- **Privacy**: No data is shared without explicit user permission
- **Email Protection**: User emails are salted and hashed (SHA256) before any export
- **Data Encryption**: Exports are encrypted using AES-256-GCM with unique keys
- **Local Storage**: User data remains on-device; no cloud integration

---

## 🤝 Contributing

Contributions are welcome! Whether you're fixing bugs, improving documentation, or adding new features, please:

1. Fork the relevant repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📝 License & Attribution

See individual repositories for license information and project-specific credits.

---

## 📞 Support & Issues

- **Bug Reports**: [OATTS Issues](https://github.com/af-oatts/oatts/issues)
- **Website Issues**: [Website Issues](https://github.com/af-oatts/af-oatts.github.io/issues)
- **General Inquiries**: Check the respective repository's issues section

---

**Built by DCS Corporation for the United States Air Force**
