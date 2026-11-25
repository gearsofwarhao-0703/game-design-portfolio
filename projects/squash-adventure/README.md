# Squash Adventure

An endless side-scrolling shooter and runner for Android and desktop Java. The character advances and fires automatically. One jump button controls obstacle clearance, firing height, and access to temporary weapons.

## Mechanics and Tuning

| Mechanic | Design |
| --- | --- |
| Jump timing | Clear short spikes with a single jump, delay the second jump for long spikes, and stay low under hanging vines. |
| Weapon pickups | Collect bubbles above the route to gain either a slow area-of-effect corn cannon or a rapid-fire pea gun. Each lasts 10 seconds. |
| Scoring | Each enemy defeated is worth 100 points. The results screen also tracks distance, hazards cleared, and the cause of failure. |
| Difficulty | The run starts at 300 virtual pixels per second, reaches 510 at one minute, and gradually approaches 900 in later play. Route spacing accounts for the speed expected when the player reaches each obstacle. |

The Android Canvas and desktop Java2D builds share a platform-independent Java model. The validation package covers jump rules, weapon timing, generated-route clearance, the speed curve, and Android input and pause behaviour. Android runtime checks were conducted on an Android 14 emulator.

## Play and Inspect

The version 1.0 package contains the Android APK, the desktop build, Java source, tests, and build instructions. Android requires version 6.0 or later. For the desktop demo, use Java 8 or later to run `SquashAdventure-desktop.jar`. [Download Squash Adventure](https://github.com/gearsofwarhao-0703/game-design-portfolio/releases/download/portfolio-v1/squash-adventure.zip)
