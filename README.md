// Blindscape VR — Unity Project Setup Template (Oculus Quest)

// ✅ Unity Version Recommended: 2022.3 LTS

// Project Structure:
/Assets
  /Scripts
    - PlayerController.cs
    - AudioPinger.cs
    - WeaponHandler.cs
    - AudioEnemy.cs
  /Prefabs
    - AudioZone.prefab
    - Enemy.prefab
    - Weapon.prefab
  /Audio
    - Steps.wav
    - EchoPing.wav
    - Whisper_Left.wav
    - Whisper_Right.wav
    - ThreatGrowl.wav
    - Gunshot.wav
    - AxeSwing.wav
  /Scenes
    - EchoesScene.unity
  /Resources
    - GameState.asset

/ProjectSettings
/Packages

// Required Packages:
// - Oculus XR Plugin
// - XR Interaction Toolkit
// - Input System

// XR Settings:
// - Enable Oculus as OpenXR runtime
// - Use XR Interaction Toolkit presets

// Key Scripts Overview:

// PlayerController.cs
// Handles movement, echolocation trigger, input mappings

// AudioPinger.cs
// Plays audio pings with configurable directionality and reverberation

// WeaponHandler.cs
// Switches between axe/gun prefabs, detects swing/fire via input

// AudioEnemy.cs
// Listens for player movement or noise, reacts with audio cue

// Scene Setup:
// - PlayerRig prefab (XR Origin)
// - AudioReverbZones for corridor depth
// - AudioSources with spatial blend = 3D
// - Colliders for interaction with invisible objects

// UI:
// No visuals — all cues are audio or haptic

// Optional (for debug):
// - Toggle for developer visual mode (faint white outlines)
// - Sound testing panel in Editor Mode only

// Notes:
// - Ensure spatial audio works correctly using headphones
// - Test on real Quest 2/3 device, not just in editor
