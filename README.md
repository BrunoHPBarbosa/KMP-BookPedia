# BookPedia App

Create a Multiplataform app for desktop, ios, android, using KMP.


## :movie_camera: Video
<img src="https://github.com/user-attachments/assets/85e4e9a2-0a2c-49be-9938-d9c3ec8f5909" width="250">&emsp;<img src="https://github.com/user-attachments/assets/f15976f7-9a48-421e-b475-a48745bcaede" width="250">&emsp;<img src="https://github.com/user-attachments/assets/36a0699c-e96d-443d-b1ae-a6999501d1b1" width="518">
## :camera_flash: Screenshots
<img src="https://github.com/user-attachments/assets/95a69fd1-a4f6-44f4-8962-31122bcd5295" width="250">&emsp;
<img src="https://github.com/user-attachments/assets/44181a53-e3b0-40a0-bfec-09a64d5335a4" width="250">&emsp;
<img src="https://github.com/user-attachments/assets/16d07be5-b6af-4752-b610-e5f8ed8bb931" width="250">&emsp;
<img src="https://github.com/user-attachments/assets/37db51be-089b-4bfd-94e4-4582bd6c1cf8" width="250">&emsp;
<img src="https://github.com/user-attachments/assets/bfdc45f6-f5c1-44de-a633-a689a5867ef0" width="250">&emsp;
<img src="https://github.com/user-attachments/assets/ab61bc43-1735-4586-9cb6-3527cbee67fd" width="250">&emsp;
<img src="https://github.com/user-attachments/assets/ef90e482-0b34-4db1-974a-a81be6e510b2" width="250">&emsp;
<img src="https://github.com/user-attachments/assets/675343f6-5539-455f-a249-9ae01a1130fa" width="500">&emsp;
<img src="https://github.com/user-attachments/assets/2ee53745-13e8-47b0-96b9-4ab243fcaf5c" width="500">&emsp;


🛠️ Technologies used

- Kotlin
- Clean Architecture
- MVVM
- Glide
- Jetpack Components (ViewBinding)

  * Clean Architecture:
    - Separação de conceitos;
    - Interface com base em modelos de dados;
    - Única fonte de informações;
    - Fonte: https://developer.android.com/topic/architecture?hl=pt-br
   
      * MVVM:
    - Separação de responsabilidades;
    - Facilidade de manutenção;
    - Testabilidade.
     
  
 * Glide 
  - É uma estrutura de gerenciamento de mídia e carregamento de imagens de código aberto rápida e eficiente para Android com uma  interface simples e fácil de usar.

 * Splash Screen
   - Utlizei a nova forma de se criar uma splash screen , mais rapida e simples , mas tambem utilizei outra forma em que adiciono um gif como tela inicial do app 



This is a Kotlin Multiplatform project targeting Android, iOS, Desktop.

* `/composeApp` is for code that will be shared across your Compose Multiplatform applications.
  It contains several subfolders:
  - `commonMain` is for code that’s common for all targets.
  - Other folders are for Kotlin code that will be compiled for only the platform indicated in the folder name.
    For example, if you want to use Apple’s CoreCrypto for the iOS part of your Kotlin app,
    `iosMain` would be the right folder for such calls.

* `/iosApp` contains iOS applications. Even if you’re sharing your UI with Compose Multiplatform, 
  you need this entry point for your iOS app. This is also where you should add SwiftUI code for your project.


Learn more about [Kotlin Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html)…
