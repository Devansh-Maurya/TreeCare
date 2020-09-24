<p align="center">
  <img src="https://raw.githubusercontent.com/Devansh-Maurya/TreeCare/master/TreeCare%20Name%20Logo.png"/>
  <h1 align = "center">A Persuasive Game to Prevent Sedentarism</h1>
</p>

A persuasive game to prevent sedentary behaviour, built for Android using Android SDK and Unity game engine. The app gamifies your daily walking activity while also allowing users to create and compete in various challenges.
The app was built as a project during the **Mitacs Globalink Research Internship at Dalhousie University in Halifax, Canada**.

TreeCare uses the metaphor of a flourishing tree with green leaves and fruits to represent someone who is physically active. In the context of this app, a person is physically active if he/she walks or runs daily. If a person does so regularly, he gets more leaves and fruits on the tree, while a tree with no leaf and fruit means zero activity. An empty tree is the default tree.

#### [Request Access to the Android App](https://forms.gle/o8bEqHwsegatzy6z6)
#### [International Conference Paper Presented at IEEE 8th International Conference on Serious Games and Applications for Health (SeGAH), Vancouver, BC, Canada, 2020](https://ieeexplore.ieee.org/document/9201637)
## Screenshots

[![Download APK](https://github.com/Devansh-Maurya/TreeCare/blob/master/Description/mode_selection.png)](https://github.com/Devansh-Maurya/TreeCare/blob/master/Description/mode_selection.png)
[![Download APK](https://github.com/Devansh-Maurya/TreeCare/blob/master/Description/tree_with_leaves.png)]()
[![Download APK](https://github.com/Devansh-Maurya/TreeCare/blob/master/Description/profile.png)](Profile)
[![Download APK](https://github.com/Devansh-Maurya/TreeCare/blob/master/Description/challenges.png)](https://github.com/Devansh-Maurya/TreeCare/blob/master/Description/challenges.png)
[![Download APK](https://github.com/Devansh-Maurya/TreeCare/blob/master/Description/leaderboard.png)](https://github.com/Devansh-Maurya/TreeCare/blob/master/Description/leaderboard.png)
[![Download APK](https://github.com/Devansh-Maurya/TreeCare/blob/master/Description/progress_report.png)](https://github.com/Devansh-Maurya/TreeCare/blob/master/Description/progress_report.png)


## Technologies Used
* **Kotlin** as the main programming language
* **MVVM Architecture** using Android Architecture Components
* **Google Fit API** for getting step count data of the user
* **LiveData, ViewModel**
* **Navigation Components** for easy navigation in the app
* **Glide** image loading library
* **Lottie** for adding animations
* **Gson** for serializing and deserializing objects
* **Material Components** for implementing the new material design
* **Koin** for Dependency Injection
* **WorkManager** for periodic background tasks
* **Coroutines** in coordination with WorkManager
* **Firebase Authentication** for Google Sign-In
* **Cloud Firestore** as the No-SQL database
* **Firebase Cloud Functions** for syncing data across users in the databse
* **Cron Job** for triggering cloud functions at a fixed time
* **Firebase Cloud Messaging** for push notifications

## Game Modes
To make the game engaging and fun, three modes are provided:
#### 1. Starter mode
#### 2. Challenger Mode
#### 3. Tournament Mode

#### PS: The Tournament Mode is still under development. In the current version, the game only has starter mode and challenger mode.
