# Mech Combat Game

![License](https://img.shields.io/github/license/toyaokeke/MechCombatGame)
![Issues](https://img.shields.io/github/issues/toyaokeke/MechCombatGame)
[![Built with](https://img.shields.io/badge/built%20with-ue4-blue)](https://www.unrealengine.com/en-US/)
![Version](https://img.shields.io/badge/version-1.0.0-orange)

# Table of Contents

- [Introduction](#introduction)
- [Supported Platforms](#supported-platforms)
- [Environment](#environment)
  - [Forest Environment](#forest-environment)
  - [Player Base](#player-base)
- [How To Play](#how-to-play)
  - [Controls](#controls)
  - [Shop Menu](#shop-menu)
  - [Heads Up Display](#heads-up-display)
- [Your Character](#characters)
  - [The Robo Dude](#the-robo-dude)
  - [The Hammer](#the-hammer)
- [Enemies](#enemies)
  - [Bomb Spiders](#bomb-spiders)
  - [Turret Spiders](#turret-spiders)
- [Items](#items)
  - [Time Fragments](#time-fragments)
- [Abilities](#abilities)
  - [Whirlwind Attack](#whirlwind-attack)
  - [Helicopter Attack](#helicopter-attack)
  - [Leap Attack](#leap-attack)
- [Building the Development Environment](#building-the-development-environment)
- [Packaging the Game for Production](#packaging-the-game-for-production)
- [Contributing Guidelines](#contributing-guidelines)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Introduction

Welcome to my Mech Combat Game! This is my first attempt at game development using Epic Game's [Unreal Engine](https://www.unrealengine.com/en-US/). It is a simple wave-based action arcade game where you control a robot and destrot mechanical spiders. If you would like to test play this game, you can either follow the instructions for [Packaging the Game for Production](#packaging-the-game-for-production) if you have the Unreal Engine, or downloading the executable from my [Dropbox link]().

![Main Menu Reference](docs/img/MainMenu/MainMenuReferance.png)

## Supported Platforms

- Windows (32-bit)
- Windows (64-bit)
- MacOS
- Linux
- Linux (AArch64)

**NOTE:** This is a desktop based game. It was not developed for gaming consoles or mobile devices. Attempting to play this game on unsupported devices will generate a warning from the game and may result in other unexpected errors.

## Environment

### Forest Environment

The main level where game exist is currently a forest environment. It is an open world environment containing bushes, trees, logs, etc. Enemies will be spawned into the environment in waves and the player will roam the area and try to survive and kill each wave of enemies.

![Forest Environment Reference](docs/img/Level1/ForestEnvironmentReference.png)

### Player Base

The player base is your home inside the forest environment. In your player base, this is where you will be able to upgrade your character's base stats, special attacks, and other things.

![Player Base Reference](docs/img/Level1/PlayerBaseReference.png)

## How To Play

### Controls

To game can be played with a mouse and keyboard. The different controls are shown below:

![Player Controls Reference](docs/img/Instructions/PlayerControlsReference.png)

### Shop Menu

The shop menu is where you can upgrade your character when you approach the workbench in your player base. You can find a sample of the shop menu below:

![Shop Menu Reference](docs/img/Instructions/ShopMenuReference.png)

### Heads Up Display

The heads up display (HUD) is where you will see your character's health, stamina, attack energy and other things. The full view of the HUD is shown below:

![HUD Reference](docs/img/Instructions/HUDReference.png)
