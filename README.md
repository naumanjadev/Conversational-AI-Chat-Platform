# Chat with Gemini AI 💬

## Overview

The Conversational AI Chat Platform is a Kotlin Compose Multiplatform project designed to target Android, iOS, Windows, macOS, Linux,
and Web platforms. It is an application by Gemini AI where you can retrieve information from text and images in a
conversational format. Additionally, it allows storing chats group-wise using SQLDelight and KStore, and facilitates
changing the Gemini API key.

## Features

- Engage in conversations from any device, including smartphones, tablets, desktops, and web browsers
- Retrieve information from text and images in a conversational format.
- Store chats group-wise using SQLDelight and KStore.
- Facilitating changing the Gemini API key.
- Simple Clean UI with Animations

# Technologies:

- Kotlin
- Clean Architecture
- Jetpack Compose for UI development
- Koin for Dependency Injection
- SQLDelight and KStore library to Store chats
- Generative AI for All AI-related stuff

## Libraries 🛠️

- [BuildKonfig](https://github.com/yshrsmz/BuildKonfig) - BuildConfig for Kotlin Multiplatform Project. It currently
  supports embedding values from gradle file.
- [Koin](https://insert-koin.io/) - Kotlin dependency injection library with multiplatform support.
- [Ktor](https://ktor.io/docs/http-client-multiplatform.html) - Provides multiplatform libraries required to make
  network calls to the REST API.
- [Kermit](https://github.com/touchlab/Kermit) - Kermit by Touchlab is a Kotlin Multiplatform centralized logging
  utility.
- [PreCompose](https://github.com/Tlaster/PreCompose) - Compose Multiplatform ViewModel and it's Kotlin Multiplatform
  project.
- [Compose Multiplatform File Picker](https://github.com/Wavesonics/compose-multiplatform-file-picker) - A multiplatform
  compose widget for picking files.
- [Multiplatform Settings](https://github.com/russhwolf/multiplatform-settings) - This is a Kotlin library for
  Multiplatform apps, so that common code can persist key-value data.
- [SQLDelight](https://cashapp.github.io/sqldelight/multiplatform_sqlite/) - Cross-Platform database library
- [KStore](https://github.com/xxfast/KStore) - A tiny Kotlin multiplatform library that assists in saving and restoring
  objects to and from disk using kotlinx.coroutines, kotlinx.serialisation and okio.
- [kotlinx.coroutines](https://github.com/Kotlin/kotlinx.coroutines) - Library support for Kotlin coroutines with
  multiplatform support.
- [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - Provides sets of libraries for various
  serialization formats eg. JSON, protocol buffers, CBOR etc.
- [kotlinx.datetime](https://github.com/Kotlin/kotlinx-datetime) - A multiplatform Kotlin library for working with date
  and time.

## Getting Started

### Installation 🛠️

1. Clone this repository:
   ```bash
   git clone https://github.com/naumanjadev/Conversational-AI-Chat-Platform.git
   ```

2. Open in the latest version of Android Studio.
3. Before running the project, obtain an API key from [Google AI](https://ai.google.dev) to communicate with the Gemini
   API.
4. Add a `local.properties` file to the project root.
5. Place your Gemini API key in `local.properties` file as `GEMINI_API_KEY` property.
```properties
GEMINI_API_KEY=YOUR_API_KEY
```
6. Configuration of SQLDelight in Android Studio:
  - Click on the Gradle icon at the top right corner.

   ![](image/install/openGradle.png)

7. Run the following Gradle tasks:
  - `generateCommonMainGeminiApiChatDBInterface`
  - `generateSqlDelightInterface`

   ![](image/install/config.png)


### Run the app on your device or emulator:

- For Android, run the `composeApp` module by selecting the `app` configuration. If you need help with the
  configuration, follow this link
  for [android](https://www.jetbrains.com/help/kotlin-multiplatform-dev/compose-multiplatform-create-first-app.html#run-your-application-on-android)
- For iOS, run the `composeApp` module by selecting the `iosApp` configuration. If you need help with the configuration,
  follow this link
  for [Ios](https://www.jetbrains.com/help/kotlin-multiplatform-dev/compose-multiplatform-create-first-app.html#run-your-application-on-ios)
- For Desktop, run `./gradlew :composeApp:run`
- For Web, run `./gradlew :composeApp:wasmJsBrowserDevelopmentRun`

## Screenshot 💻

## Website Images

<table>
   <tr>
      <td><img src="image/web/web1.png" alt="web"></td>
       </tr>
  <tr>
      <td><img src="image/web/web2.png" alt="web"></td>
   </tr>
   <tr>
      <td><img src="image/web/web3.png" alt="web"></td>
       </tr>
  <tr>
      <td><img src="image/web/web4.png" alt="web"></td>
   </tr>
   <tr>
      <td><img src="image/web/web5.png" alt="web"></td>
       </tr>
  <tr>
      <td><img src="image/web/web6.png" alt="web"></td>
   </tr>
   <tr>
      <td><img src="image/web/web7.png" alt="web"></td>
       </tr>
  <tr>
      <td><img src="image/web/web8.png" alt="web"></td>
   </tr>
   <tr>
      <td><img src="image/web/web9.png" alt="web"></td>
       </tr>
  <tr>
      <td><img src="image/web/web10.png" alt="web"></td>
   </tr>
</table>



## Window

<table>
  <tr>
    <td><img src="image/windows/win1.png" alt="win"></td>
      </tr>
  <tr>
    <td><img src="image/windows/win2.png" alt="win"></td>
  </tr>
  <tr>
    <td><img src="image/windows/win3.png" alt="win"></td>
      </tr>
  <tr>
    <td><img src="image/windows/win4.png" alt="win"></td>
  </tr>
  <tr>
    <td><img src="image/windows/win5.png" alt="win"></td>
      </tr>
  <tr>
    <td><img src="image/windows/win6.png" alt="win"></td>
  </tr>
  <tr>
    <td><img src="image/windows/win7.png" alt="win"></td>
      </tr>
  <tr>
    <td><img src="image/windows/win8.png" alt="win"></td>
  </tr>
  <tr>
    <td><img src="image/windows/win9.png" alt="win"></td>
      </tr>
  <tr>
    <td><img src="image/windows/win10.png" alt="win"></td>
  </tr>
</table>

## Mac

<table>
   <tr>
      <td><img src="image/mac/mac1.jpeg" alt="mac"></td>
       </tr>
  <tr>
      <td><img src="image/mac/mac2.png" alt="mac"></td>
   </tr>
   <tr>
      <td><img src="image/mac/mac3.jpeg" alt="mac"></td>
       </tr>
  <tr>
      <td><img src="image/mac/mac4.jpeg" alt="mac"></td>
   </tr>
   <tr>
      <td><img src="image/mac/mac5.jpeg" alt="mac"></td>
       </tr>
  <tr>
      <td><img src="image/mac/mac6.jpeg" alt="mac"></td>
   </tr>
   <tr>
      <td><img src="image/mac/mac7.jpeg" alt="mac"></td>
       </tr>
  <tr>
      <td><img src="image/mac/mac8.jpeg" alt="mac"></td>
   </tr>
   <tr>
      <td><img src="image/mac/mac9.jpeg" alt="mac"></td>
       </tr>
  <tr>
      <td><img src="image/mac/mac10.jpeg" alt="mac"></td>
   </tr>
</table>


 ## Android

<table>
   <tr>
    <td><img src="image/android/android1.png" alt="android"></td>
    <td><img src="image/android/android2.png" alt="android"></td>
   </tr>
   <tr>
    <td><img src="image/android/android3.png" alt="android"></td>
    <td><img src="image/android/android4.png" alt="android"></td>
   </tr>
   <tr>
    <td><img src="image/android/android5.png" alt="android"></td>
    <td><img src="image/android/android6.png" alt="android"></td>
   </tr>
   <tr>
    <td><img src="image/android/android7.png" alt="android"></td>
    <td><img src="image/android/android8.png" alt="android"></td>
       </tr>
   <tr>
    <td><img src="image/android/android9.png" alt="android"></td>
   </tr>
</table>
