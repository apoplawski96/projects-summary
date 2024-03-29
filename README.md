<a href="https://github.com/apoplawski96/projects-summary/blob/master/assets/apoplawski_banner.png?raw=true"><img src="https://github.com/apoplawski96/projects-summary/blob/master/assets/apoplawski_banner.png?raw=true"></a>

<h1 align="center"> MY NON-COMMERCIAL PROJECTS / RECRUITMENT TASKS </h4>

<p><h1 align="center"><a href="https://github.com/apoplawski96/kti-multiplatform">Interview App</a></h1></p>

<img align="center" src="https://github.com/apoplawski96/projects-summary/blob/master/assets/kti_mockup.png" /></a>
<br> 
<br>
"KillTheInterview" is a [Kotlin Multiplatform Mobile][kmm] app, which purpose is to help users prepare for a technical job interview. App main features are:
- Interview simulation, using either curated questions pool or AI powered
- Learning with curated questions & answers pool

## Architecture

Project is built out of [KaMPKit][kampkit], which is a starter project for Kotlin Multiplatform Mobile apps.
The app is written in MVVM/MVI, aiming to follow [Modern App Architecture][modernAppArchitecture] guidelines throughout both, Android and KMM modules.

### Objectives:
- Layered architecture with data, domain & UI layers
- Unidireactional Data Flow, Single Soure Of Truth
- Sharing as much code as possible in KMM module, so it can be reused throughout platforms
- Testability

Android module follows single-Activity architecture with Compose Navigation, where each screen has its own ViewModel from KMM module. iOS module development is not yet started.
  
### Tech stack:
- Kotlin Multiplatform Mobile
- MVVM/MVI
- Coroutines, Flows
- Compose
- Koin
- OpenAI API
- SQL Delight
- Json

 [modernAppArchitecture]: https://developer.android.com/topic/architecture#modern-app-architecture
 [kmm]: https://kotlinlang.org/docs/multiplatform-mobile-getting-started.html
 [kampkit]: https://github.com/touchlab/KaMPKit
  
<p><h1 align="center"><a href="https://github.com/apoplawski96/dacompazzz">Compass App</a></h1></p>

<img align="center" src="https://github.com/apoplawski96/projects-summary/blob/master/assets/DaCompazzz.jpg" /></a>
<br> 
<br>
Compass Project is a simple compass, which displays a direction for the user to follow. It has a feature
to indicate the destination based on a geographic coordinate system. It makes it easy for the user to
enter the latitude and longitude coordinates and navigate towards the location. I wrote this app as recruitment task which succesffully led me to the next stage.
  
### Tech stack:
- Kotlin (~95%)
- Java (SensorReadingNormalizer && MathUtilsLegacy classes)
- MVP
- Dagger 2
- Location
- Canvas
- JUnit 4
- Mockito
- AssertJ

<p><h1 align="center"><a href="https://github.com/apoplawski96/medium-code-samples">Medium Code Samples</a></h1></p>
This is a repository where I host ready-to-compile practical examples for my Medium articles/tutorials.
<br>
https://medium.com/@a.poplawski96
  
### Tech stack:
- Kotlin
- MVVM\MVI
- Clean Architecture / Modern App Architecture
- Koin
- Compose
- Coroutines, StateFlow
- JUnit 5
- Mockk

<p><h1 align="center"><a href="https://github.com/apoplawski96/rewardsApp">Rewards App</a></h1></p>
The purpose of this app is to let user to activate rewards, taking his account balance into consideration. The app has to connect with RewardsAPI that simulates regular remote API. The API also throws exceptions that have to be handled. I wrote this app as recruitment task which succesffully led me to the next stage.
  
### Tech stack:
- Kotlin
- MVVM
- Multi modular
- Clean Architecture
- Koin
- Compose
- Coroutines, StateFlow
- JUnit 5
- Mockk

<br>
<br>
<br>
<p><h1></h1></p>
<p><h1 align="center"> NOTE: All projects included below have been created before I started working commercially as Android Developer, therefore its code, architecture and applied solutions do not reflect my current state of skills and knowledge. </h1><p>
<br>
<br>
<br>
  
<p><h1 align="center"><a href="https://github.com/apoplawski96/ricknmortyapiclient">RickNMorty App</a></h1></p>

<img align="center" src="https://github.com/apoplawski96/projects-summary/blob/master/assets/ricknmortyapiclient.jpg" /></a>
<br> 
<br>
This is a simple app that fetches data from Rick And Morty API and displays it. I wrote this app as recruitment task. It's a multi-module app built in MVP pattern, using Dagger2, RxJava and Retrofit2.
  
## Project structure
* **ricknmorty** - contains all the app specific code
* **app** - dependency configuration of application
* **base** - code that could be used in different modules or apps with similar technology stack
### Tech stack:
- Kotlin
- MVP
- RxJava2
- Dagger2
- Retrofit2
- Glide
- DiffUtil
- JUnit
- Mockito
- AssertJ


<p><h1 align="center"><a href="https://github.com/apoplawski96/ArtistManagerApp">ArtistManagementApp</a></h1></p>
<img align="center" src="https://github.com/apoplawski96/projects-summary/blob/master/assets/ArtistManagementApp.png" /></a>
<p><h3 align="center">
  Kotlin •
  Firebase Cloud Firestore •
  Firebase Auth •
  Firebase Storage
</h3></p>

<p> This app is a project for my bachelor's degree thesis. App's purpose is to provide a platform to manage and organise everyday's workload concerning the artist or the manager of a music band/music project.</p>
<p> It's writen solely in <b>Kotlin</b>, using <b>Firebase</b> as a backend service. </p>
<p> It has functionalities like: <b>user authentication</b> (login, register, change password, etc), <b>Task Manager</b> (add task, delete task, complete task, change due date, etc) and many more.</p>

<p><h1 align="center"><a href="https://github.com/apoplawski96/music-club-journal-app">"STK-47 Warehouse Music Club" Journal App</a></h1></p>
<img align="center" src="https://github.com/apoplawski96/projects-summary/blob/master/stk_promo.png" /></a>
<p><h3 align="center">
  Kotlin •
  MVVM •
  Firebase Cloud Firestore •
  LiveData •
  Kodein
</h3></p>



<p> This is an app made for a music club.
It's purpose is to store clubs' upcoming events, past events, artists that played there, and to present it in nice way,
that fit's the club's theme. It's build using <b>MVVM</b> design pattern, <b>Kodein</b> for dependency injection, <b>Firebase</b>, <b>Navigation Component</b> and <b>LiveData</b>.</p>



<p><h1 align="center"><a href="https://github.com/apoplawski96/sport-events-app">Sport Events App (Recruitment task)</a></h1></p>
<img align="center" width="300" src="https://github.com/apoplawski96/projects-summary/blob/master/recrutaskss.jpg" /></a>
<p><h3 align="center">
  Kotlin •
  MVVM •
  Room •
  Coroutines •
  LiveData •
  Kodein •
  ExoPlayer •
  Navigation •
  Retrofit2 •
  Glide •
  DiffUtil
</h3></p>

<p> The app is built in <strong>MVVM</strong> design pattern, writen solely in <strong>Kotlin</strong>. For concurrency and reactive programming tools I decided to go with <strong>LiveData</strong> and <strong>Coroutines</strong>. The app fetches the data from the network using <strong>Retrofit2</strong>, then stores it locally with help of <strong>Room</strong> library. It uses <strong>Kodein</strong> for dependency injection..</p>
<p> <strong>NOTICE:</strong> This app was a code challenge from my first, successfull recruitment process for a junior developer role. </p>


## Contact

✉️ a.poplawski96@gmail.com
<br>
👷 <a href="http://www.linkedin.com/in/apoplawski96/">linkedin.com/in/apoplawski96/</a>
