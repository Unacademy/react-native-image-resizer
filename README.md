# react-native-image-resizer

> 🗻 Resize local images with React Native

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**react-native-image-resizer** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

🗻 Resize local images with React Native

**Topics / Tags:** _None_

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | Unknown |
| **Framework / Platform** | Unknown |
| **Package Manager** | — |

### Dependencies

**Dev Dependencies:**
- `cz-conventional-changelog`


---

## Repository Structure

```
react-native-image-resizer/
├── .gitignore
├── .npmignore
├── .prettierrc
├── LICENSE
├── README.md
├── android/
│   ├── build.gradle
│   ├── gradle
│   ├── gradlew
│   ├── gradlew.bat
│   ├── src
├── common.js
├── docs
├── example/
│   ├── .buckconfig
│   ├── .eslintrc.js
│   ├── .flowconfig
│   ├── .gitattributes
│   ├── .gitignore
├── index.d.ts
├── index.js
├── index.js.flow
├── ios/
│   ├── RCTImageResizer
│   ├── RCTImageResizer.xcodeproj
├── package.json
├── react-native-image-resizer.podspec
├── yarn.lock
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|
| `LICENSE` | Source file |
| `README.md` | Source file |
| `android/build.gradle` | Source file |
| `android/gradle/wrapper/gradle-wrapper.jar` | Source file |
| `android/gradle/wrapper/gradle-wrapper.properties` | Source file |
| `android/gradlew` | Source file |
| `android/gradlew.bat` | Source file |
| `android/src/main/AndroidManifest.xml` | Source file |
| `android/src/main/java/fr/bamlab/rnimageresizer/ImageResizer.java` | Source file |
| `android/src/main/java/fr/bamlab/rnimageresizer/ImageResizerModule.java` | Source file |
| `android/src/main/java/fr/bamlab/rnimageresizer/ImageResizerPackage.java` | Source file |
| `common.js` | Source file |
| `docs/android_manual_config.md` | Source file |
| `example/.buckconfig` | Source file |
| `example/.eslintrc.js` | Source file |
| `example/.flowconfig` | Source file |
| `example/.gitattributes` | Source file |

> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- Unknown runtime installed



### Steps

```bash
git clone git@github.com:unacademy/react-native-image-resizer.git
cd react-native-image-resizer
# Follow language-specific setup
```


---

## Running the Application

_Refer to the project's build system or CI configuration._

---

## Infrastructure & CI/CD

- Test suite present — run tests before submitting PRs

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `master`
4. Ensure all CI checks pass before requesting review

---

## Original README (Excerpt)

> # React Native Image Resizer

A React Native module that can create scaled versions of local images (also supports the assets library on iOS).
|react-native| react-native-image-resizer|
| --- | --- |
| ≤ 0.60 | 1.1.0 |
| 0.61 | 1.2.0 |

## Setup

Install the package:

- React Native >= 0.60

```
yarn add react-native-image-resizer
cd ios && pod install
```

- React Native <= 0.59

```
yarn add react-native-image-resizer
react-native link react-native-image-resizer
```

### Android

Note: on latest versions of React Native, you may have an error during the Gradle build on Android (`com.android.

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*
