<p align="center">
  <img src="https://raw.githubusercontent.com/Devansh-Maurya/TreeCare/master/TreeCare%20Name%20Logo.png"/>
  <h1 align = "center">A Persuasive Game to Prevent Sedentarism</h1>
</p>

[![Download APK](https://img.shields.io/badge/APK-Download-%233DDC84)](https://github.com/Devansh-Maurya/TreeCare/raw/master/TreeCare.apk)

A persuasive game to prevent sedentary behaviour, built for Android using Android SDK and Unity game engine. The app gamifies your daily walking activity while also allowing users to create and compete in various challenges.

#### Android repository:  [https://github.com/Devansh-Maurya/TreeCare-Android](https://github.com/Devansh-Maurya/TreeCare-Android)
#### Unity repository:    [https://github.com/Devansh-Maurya/TreeCare-Unity](https://github.com/Devansh-Maurya/TreeCare-Unity)

TreeCare uses the metaphor of a flourishing tree with green leaves and fruits to represent someone who is physically active. In the context of this app, a person is physically active if he/she walks or runs daily. If a person does so regularly, he gets more leaves and fruits on the tree (Figure 1), while a tree with no leaf and fruit means zero activity (Figure 2). Figure 2 is the default tree.

![Tree images](https://raw.githubusercontent.com/Devansh-Maurya/TreeCare/master/Description/TreeImages.png) 

## Game Modes
To make the game engaging and fun, three modes are provided:
#### 1. Starter mode
#### 2. Challenger Mode
#### 3. Tournament Mode

## 1. Starter Mode

This is a single player mode. Here are the rules of this mode:

1. A player’s daily goal is initially set as 5,000 steps which can be increased by him.
2. For every 1,000 steps taken in a day, the player gains a green leaf.
3. When the player fails to meet his daily goal, he loses the number of leaves that corresponds to the remaining steps required to meet his goal. In other words

<p align="center"><a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\LARGE&space;leavesLost&space;=&space;ceil&space;\left&space;(&space;\frac{dailyGoal&space;-&space;totalSteps}{1000}&space;\right&space;)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\LARGE&space;leavesLost&space;=&space;ceil&space;\left&space;(&space;\frac{dailyGoal&space;-&space;totalSteps}{1000}&space;\right&space;)" title="\LARGE leavesLost = ceil \left ( \frac{dailyGoal - totalSteps}{1000} \right )" /></a></p>

4. If the player meets his daily goal consistently for a week, he gains a fruit on his tree
5. But, if the player fails to fulfil his daily goals for a week, he loses a fruit (if any).

## 2. Challenger Mode
This is an individual-based competitive mode where a player competes with other player(s). Here are the rules of this mode:

1. The rules in the Starter Mode also apply to every player in this mode.
2. A player can see various active challenges (created by other players) and can choose to join any of them to compete. Alternatively, he can create his own challenge by inviting other players to compete with him.
3. To publicly recognize players’ efforts, there is a leaderboard that ranks top 10 players in descending order of the number of leaves and fruits on their trees.
4. Every challenge has a timeline which is set by the organizer. Only the top 10 players are rewarded with a trophy corresponding to their position.
5. Every player starts a challenge with the default tree (Figure 2).

## 3. Tournament Mode
This is a team-based mode where a team of N players competes with another team of N players. Each team has a default tree to nurture (Figure 2). Here are the rules of the tournament mode:

1. The daily goal is initially set to 20,000 steps and the teams in a tournament can decide to increase this goal upon agreement.
2. For every 3,000 steps taken in a day, a team gains a green leaf on its tree.
3. When a team fails to meet its daily goal, it loses the number of leaves that corresponds
to the remaining steps required to meet the goal. In other words,

<p align="center"><a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\LARGE&space;leavesLost&space;=&space;ceil&space;\left&space;(&space;\frac{dailyGoal&space;-&space;totalSteps}{3000}&space;\right&space;)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\LARGE&space;leavesLost&space;=&space;ceil&space;\left&space;(&space;\frac{dailyGoal&space;-&space;totalSteps}{3000}&space;\right&space;)" title="\LARGE leavesLost = ceil \left ( \frac{dailyGoal - totalSteps}{3000} \right )" /></a></p>

4. If a team meets its daily goal consistently for a week, a fruit appears on its tree.
5. But, if the team fails to fulfil its daily goals for a week, a fruit disappears (if any)

#### Note: The Tournament Mode is still under development. In the current version, the game only has starter mode and challenger mode.
