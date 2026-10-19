<!-- DELETE ME -->
# About this template

This is a repository template specialized for Android applications developed with Android Studio. It comes with:

- Kotlin and Jetpack Compose
- Gradle version catalog and wrapper
- A single-activity Compose application with a preview
- Unit tests with JUnit
- GitHub Actions for lint, unit tests, and debug APK builds
- Dependabot for Gradle and GitHub Actions

<hr>
<!-- DELETE ME -->
<a name="readme-top"></a>

<!-- Presentation Block -->
<br />

<div align="center">

  <a href="https://github.com/LightDestory/AndroidRepoTemplate/">
    <img src="https://raw.githubusercontent.com/LightDestory/AndroidRepoTemplate/master/.github/assets/images/presentation_image.png" alt="Preview" width="90%">
  </a>

  <h2 align="center">PROJECT_NAME</h2>

  <p align="center">
      PROJECT_SHORT_DESCRIPTION
  </p>

  <br />
  <br />

</div>

<!-- ToC -->

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#book-about-the-project">📖 About The Project</a>
    </li>
    <li>
      <a href="#gear-getting-started">⚙️ Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#notes">Notes</a></li>
      </ul>
    </li>
    <li><a href="#dizzy-contributing">💫 Contributing</a></li>
    <li><a href="#handshake-support">🤝 Support</a></li>
    <li><a href="#warning-license">⚠️ License</a></li>
    <li><a href="#hammer_and_wrench-built-with">🛠️ Built With</a></li>
  </ol>
</details>

<!-- About Block -->

## :book: About The Project

PROJECT_LONG_DESCRIPTION

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Setup Block -->

## :gear: Getting Started

START_INFO

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Prerequisites

__Make sure to have Android Studio and JDK 17 installed on your system.__

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Installation

- Clone the repository:
    - `git clone https://github.com/LightDestory/AndroidRepoTemplate`
- Open the [Android variant](https://github.com/LightDestory/AndroidRepoTemplate/) in Android Studio.
- Let Gradle sync the project and install any missing SDK packages.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Usage

- Build a debug APK from the command line:
    - `./gradlew assembleDebug`
- Run unit tests:
    - `./gradlew testDebugUnitTest`
- Run lint:
    - `./gradlew lintDebug`
- Install the debug APK on a connected device:
    - `./gradlew installDebug`

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Notes

- The application package is `com.example.androidtemplate`; rename it for your project.
- `minSdk` is 26, `targetSdk` is 37, and `compileSdk` is 37.
- On macOS or Linux, run `chmod +x gradlew` once if the wrapper is not executable.
- The launcher icon is an adaptive icon built from vector resources, so there are no bitmap assets to maintain.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Contribute Block -->

## :dizzy: Contributing

If you are interested in contributing, please refer to [Contributing Guidelines](https://github.com/LightDestory/AndroidRepoTemplate/blob/master/.github/CONTRIBUTING.md) for more information and take a look at open issues. Ask any questions you may have and you will be provided guidance on how to get started.

Thank you for considering contributing.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Support Block -->

## :handshake: Support

If you find value in my work, please consider making a donation to help me create, and improve my projects.

Your donation will go a long way in helping me continue to create free software that can benefit people around the world.

<p align="center">
<a href='https://ko-fi.com/M4M6KC01A' target='_blank'><img src='https://raw.githubusercontent.com/LightDestory/AndroidRepoTemplate/master/.github/assets/images/support.png' alt='Buy Me a Hot Chocolate at ko-fi.com' width="45%" /></a>
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- License Block -->

## :warning: License

The content of this repository is distributed under the GNU GPL-3.0 License. See [LICENSE](https://github.com/LightDestory/AndroidRepoTemplate/blob/master/LICENSE) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Built With Block -->

## :hammer_and_wrench: Built With

- [Kotlin](https://kotlinlang.org/)
- [Jetpack Compose](https://developer.android.com/compose)
- [Gradle](https://gradle.org/)
- [Android Studio](https://developer.android.com/studio)
- [GitHub Actions](https://github.com/features/actions)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
