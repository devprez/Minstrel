# Minstrel

A Unity + FMOD first-person exploration game built around adaptive music, interactive audio, and state-driven progression.

Minstrel began as **Wanderer**, a small adaptive-audio prototype inspired by a song concept. As the project grew, Wanderer became the first level and musical foundation for a broader game centered on exploration, discovery, and a soundtrack that changes with the player.

## Level One: Wanderer

The first level, **Wanderer**, introduces the core idea:

the player explores an environment, discovers musical relics, and gradually rebuilds the soundtrack through play.

Each recovered relic adds a new musical layer to the arrangement, making progression audible as well as visible.

Current musical stems include:

- Guitars
- Keys
- Bass
- Drums

## Current Features

- First-person exploration in Unity
- FMOD integration
- Adaptive music built from layered stems
- Collectible musical relics
- Game-state-driven soundtrack changes
- Environmental ambience
- Parameter-based audio control
- Return-journey state changes
- Gameplay systems written in C#

## Audio System

FMOD is used to manage the interactive soundtrack and environmental audio.

The main music event responds to gameplay by enabling and transitioning between musical layers as the player explores the level and collects relics.

Parameters such as area and journey state allow the soundtrack to react to where the player is and what stage of the experience they have reached.

The goal is to make the music feel like part of the game system rather than background playback.

## Tech

- **Unity**
- **C#**
- **FMOD Studio**
- Adaptive music systems
- Interactive sound design
- Event-driven gameplay logic
- Git / GitHub

## In Development

- Expanded `JourneyState` behavior
- Additional footsteps and environmental sound
- More polished visual presentation
- New areas and levels beyond Wanderer
- Improved adaptive transitions
- Additional sound-design work
- Portfolio-ready playable build

## Project Direction

Minstrel is evolving from a focused adaptive-audio demo into a broader interactive music project.

Future levels can explore different musical structures, environments, and relationships between player behavior and sound while sharing the same underlying gameplay and audio architecture.

## Portfolio Goal

Minstrel is designed to demonstrate:

- Unity / C# development
- FMOD implementation
- adaptive music design
- interactive audio systems
- gameplay-driven sound
- state-based system architecture
- integration between music, sound, and player experience

## Status

Active development.

The core adaptive-audio system is working, with additional gameplay, visual, and sound-design polish underway.
