# Real Take

A third-person narrative mission prototype built in Unity. The player follows a lead from an apartment to a warehouse, survives a fight, escapes a pursuing vehicle, and delivers a ledger to the police.

## Mission Structure

| Beat | Gameplay | Design Focus |
| --- | --- | --- |
| Apartment | Examine personal objects and receive a note. | Tell the character's backstory through optional interactions. |
| Warehouse | Watch the 64-second opening scene, then fight through three waves. | Teach light attacks, heavy attacks, counters, dodges, and finishers within the mission. |
| Pursuit | Follow the route, lose the trailing vehicles, and hear an in-game radio broadcast. | Keep the player driving while the story continues through audio. |
| Investigation and Handoff | Examine three ledger entries and hand the evidence to an officer. | Convey the conclusion through a physical handoff. |

Combat uses distinct cues for attacks that can be countered and attacks that need to be dodged. Only one enemy starts an attack against the player at a time. The main menu also offers separate entry points for the cutscene, combat tutorial, and pursuit.

Version 1.7 refined the investigation labels, fixed sleeve clipping during cutscenes, and revised the ledger handoff animation.

## Play and Inspect

The package includes the Windows build, the Unity project, three design documents, four scene plans, and seven gameplay videos. After extraction, run `RealTake.exe` and select the full mission or a chapter. The Unity entry scene is `Assets/Scenes/Main.unity`. [Download Real Take](https://github.com/gearsofwarhao-0703/game-design-portfolio/releases/download/portfolio-v1/real-take.zip)
