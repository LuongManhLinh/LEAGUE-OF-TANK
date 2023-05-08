# League of Tank - A-SDL2-C++-Game

## Introduction

A game project made with SDL2 C++.

Game's demo: https://youtu.be/0lNHREqGOJo

## Project uses:
- SDL2 2.26.3 mingw.
- SDL2 image 2.6.3 mingw.
- SDL2 mixer 2.6.3 mingw.
- SDL2 ttf devel 2.20.2 mingw.

## Contents

### How to download and set up the game

- Clone this repository to your computer

- Extract file LEAGUE_OF_TANK.zip

- Find file LEAGUE_OF_TANK.exe, mouse right-click on this file -> Properties -> Compatibility 
  -> Change high DPI settings -> check the box in High DPI scaling override, 
  then choose OK and Apply this.

- Run file LEAGUE_OF_TANK.exe to play the game

## Game discription

You are tasked with attacking the enemy base with only a regular tank. How can you complete the mission successfully?

The ultimate goal of the game is to destroy the enemy's main house (base) within a certain time frame. At the beginning of the game, with the strength of a tank, players can attack and destroy the opponent's tank. However, this strength is not enough to attack the opponent's protective turret and main house. Therefore, what players should do when they first enter the game is not to rush into attacking the enemy's base, but to farm for resources. When there are enough resources, players can return to their base to upgrade the tank. When the tank is strong enough, then players can consider attacking the opponent's main house.

However, farming for resources is not easy. The locations of the resource mines will have enemy tanks guarding them. This is a difficult point, but also an advantage, because when players destroy the enemy tank, they will receive a certain amount of ore by touching that tank.

Remember that the maximum load capacity of your tank is 200 ores (or a little more). When the tank is full, you cannot collect any more. So return to the base to store the ores.

The function of our base is to reload ammunition, repair the tank (restore health and armor), and upgrade the tank.

After a period of time, the mined ores will be replenished, so take advantage of that opportunity to collect resources.

The enemy will not stay the same and will become stronger. Specifically, every 2 minutes, their health will increase by 1, and when you upgrade your tank, a random enemy tank will also be upgraded similarly. So pay attention to this point.

We know when we win, so when do we lose? Since our main house will not be attacked, the game will end when you cannot destroy the enemy's main house within the time frame of the mission, or when the number of times the tank dies exceeds the limit (then the base cannot repair the tank anymore).

In this version, the mission time is 12 minutes, and the maximum number of times your tank can die is 5 times.

**Controls:**

- W, A, S, D: Move

- Mouse left-click: Shoot

- Mouse right-click: Reload bullets

- R : Open upgrades table:
  + Press numbers to choose upgrade type
  + Press Enter to upgrade

- F : Show informations (levels, stored ores)

- Esc: Pause the game
