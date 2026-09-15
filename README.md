# Wanderer

A Unity + FMOD first-person exploration prototype built to demonstrate adaptive music, interactive audio, and state-driven game systems.

The player explores a sparse environment, discovers musical relics, and changes the soundtrack through play. Each recovered element adds to the arrangement, turning movement through the level into a musical progression.

## Current Features

- First-person exploration in Unity
- FMOD integration
- Adaptive music built from layered stems
- Game-state-driven audio changes
- Collectible relic system
- Music progression tied to player exploration
- Separate ambience event for environmental sound
- Parameter-based control of musical state

## Audio System

The main music event uses layered stems for:

- Guitars
- Keys
- Bass
- Drums

As the player discovers relics, the musical arrangement changes dynamically. The goal is to make progression audible as well as visible, with the soundtrack responding directly to what the player has done.

FMOD parameters are used to control transitions between areas and journey states while keeping musical changes seamless.

## Tech

- **Unity**
- **C#**
- **FMOD Studio**
- Adaptive / interactive music systems
- Event-driven game logic
- Git / GitHub

## In Development

- Expanded `JourneyState` behavior for the return trip
- Additional environmental audio and footsteps
- Improved visual presentation
- New exploration area / level work
- Further adaptive music transitions
- More polished playable portfolio build

## Portfolio Goal

Wanderer is a game-audio and technical-design portfolio project demonstrating:

- Unity / C# development
- FMOD implementation
- adaptive music design
- state-driven audio systems
- interactive sound design
- integration between gameplay and music

## Status

Active development. The core adaptive-audio system is working, with additional gameplay, visual, and sound-design polish planned.
