Project Log Assignments

Module Six Team Project Plans:
From an artist’s standpoint, this stage of development has been challenging due to technical issues that directly affected our ability to complete gameplay and visual features. While our plan from Module Three focused on continuing development into polish and final implementation, our progress was impacted by a major issue with the player character asset.

A mistake pushing the player character to the repository incorrectly caused conflicts across the team. As a result, some members, including me, lost access to a working version of the player character. One of my teammates had to recreate it from scratch, but even after that, I still cannot properly access or use the updated file in my project. This has prevented me from continuing key parts of my work.

One area that went well was the base setup for the AI systems. I was able to create three different enemy types with basic behaviors, such as chasing the player. This helped establish a strong foundation for gameplay.

However, many planned features could not be completed. I have not been able to implement the health system for the AI, and collision interactions are not working because the player character reference is missing or incompatible. I am also responsible for teleporters and jump pads, but I cannot complete those systems since they rely on player collision. Even if I build them, I cannot properly link them without a working player character.

Previous feedback was partially applied, especially in expanding AI behavior, but most of this stage was spent troubleshooting instead of improving or polishing. This slowed down overall progress.

To improve our development process, we need better communication and stronger version control practices. One incorrect push caused issues for multiple team members, underscoring the importance of verifying changes before updating the repository. Creating backups and being more careful with merging would help avoid this in the future.

While Git is useful, it can be challenging when dealing with .uasset files, as errors are harder to fix. Additionally, many tutorials we used were outdated or did not match our setup, which made solving problems more difficult.

At this stage, we have a working foundation for AI and level structure. Still, important systems like health, collision interactions, teleporters, and jump pads are incomplete due to the ongoing player character issue. Until that is resolved, progress will remain limited.

Overall, this experience showed how dependent artistic and gameplay development is on stable technical systems and strong team coordination.

Contributors:
  • Sky Sin
  • Ryan Lopez
  • Alexa Bairos
  • Adam Mack


Module Five Team Project Plans:
Plan Evaluation (Technical/Programming Perspective):
During this stage of development, the team continued building upon the systems established in previous weeks, focusing on improving functionality and resolving issues identified during the Alpha stage. From a technical standpoint, progress has been steady, especially with core gameplay systems such as player movement and enemy AI.
One aspect that went well was the continued implementation and testing of core systems. The Enemy AI system has improved, as enemies are now able to detect and move toward the player correctly. Additionally, the team has begun expanding enemy variations by introducing multiple AI types, including one that incorporates ranged (shooting) behavior. A health pickup has also been successfully implemented and is functioning as intended when interacting with the player. This shows clear progression toward a more complete and engaging gameplay experience.
However, some parts of the plan did not go as expected. While the Enemy AI can successfully chase the player, an issue persists where the AI does not properly return to its “Wander” state after losing the player. This indicates that additional work is needed in refining behavior transitions and AI logic. Another challenge encountered was related to version control. Earlier in the development process, incorrect merging caused confusion in the repository, but this has since been resolved, and the proper Git workflow is now consistently followed.

Integration of Previous Evaluations:
Feedback from the previous stage (Alpha) was used to guide improvements in both gameplay systems and team workflow. For example, issues with AI behavior identified during earlier testing led to adjustments to the chase logic, allowing enemies to track the player again properly. Additionally, lessons learned from earlier Git errors have helped the team improve how it manages branches, merges, and repository updates, reducing the likelihood of similar issues in the future.

Collaboration and Development Improvements:
To improve collaboration and development, the team has become more structured in task assignment. Each member is now focusing on specific areas of the project based on their strengths. For example, Enemy AI development is being handled separately from UI and pickups, allowing for more focused progress.
One improvement moving forward would be better coordination when integrating systems. While individual components are being developed successfully, more frequent testing of combined systems (AI + player + pickups) would help identify issues earlier and improve overall stability.

Tools and Techniques Evaluation:
The team has primarily used Unreal Engine, GitHub, and Discord for development and communication. Discord has been effective for quick communication and troubleshooting, while GitHub has been essential for version control.
However, some challenges were encountered with learning resources. Many available tutorials are outdated or do not fully match the current version of Unreal Engine. Additionally, some tutorials do not cover specific features needed for this project (such as detailed AI behavior transitions), making it more difficult to find direct solutions. As a result, more time has been spent experimenting and troubleshooting independently.

Current Beta Development Status:
At the Beta stage, the project has reached a mostly functional state with core systems implemented. The following progress has been made:
  - Enemy AI successfully detects and chases the player
  - Multiple enemy types are being developed (including a shooting variant)
  - Health pickup is implemented and functional
  - Core gameplay systems are in place
Currently in progress:
  - Fixing AI behavior so enemies return to wandering after losing the player
  - Implementing health and damage systems for all enemy types
  - Finalizing multiple enemy variations
Once these systems are complete, development will move forward to implementing teleporters and jump pads as soon as possible.

Project Schedule and Final Release Plan:
The team remains aligned with the overall project timeline. While some technical challenges have caused minor delays, progress is still being made toward meeting the final release deadline. The immediate focus is on completing AI behavior and health systems, followed by implementation of the remaining level mechanics (teleporters and jump pads), and final testing and polishing.

Contributors:
  • Sky Sin
  • Ryan Lopez
  • Alexa Bairos
  • Adam Mack


Module Four Team Project Plan:
Team QA and Testing Reflection:
During the QA and testing process for our Alpha build, several aspects of the project went well. The player character movement is functioning correctly, and the enemy AI is successfully moving within the level. The enemy AI can detect the player and move toward the player when in range, confirming that the basic behavior system is working as intended.

Bug Identification and Fixes:
One issue identified during testing is that when the enemy AI makes contact with the player, it stops moving entirely and does not resume wandering. This indicates a problem in the behavior logic or state transition between actions. Bugs like this were identified through playtesting and observing how the AI reacts during gameplay.
To address this issue, I plan to implement a separate "Chase" sequence to better control how the enemy transitions between wandering and pursuing the player. This should allow for smoother behavior switching. After resolving movement issues, the next step will be implementing health and damage systems for both the player and enemies.

Improvements for QA Process:
To improve our QA and testing process, we would benefit from more structured, repeatable testing sessions focused on specific systems, such as AI behavior and player interaction. Creating more detailed test cases for each feature helps identify issues earlier and makes debugging more efficient.

Tools and Techniques:
The tools selected in Module Two, such as Unreal Engine and Discord, were effective for our development process. Unreal Engine enabled us to test gameplay features with Blueprints quickly, and Discord helped us communicate issues and updates in real time. These tools made collaboration easier and allowed us to identify and discuss bugs quickly.
One area that could be improved is the better organization of testing feedback. While communication was effective, having a more structured way to track bugs (such as a shared bug list or issue tracker) would improve efficiency and clarity.

Design Decisions and Tool Usage:
Our initial analysis of the game design document helped guide our choice of tools and development approach. Since our project involves AI behavior, player interaction, and level design, Unreal Engine was a strong fit due to its Blueprint system and real-time testing capabilities. Our decision to split responsibilities based on team strengths also helped us use these tools more effectively.

Next Steps for Development:
As part of the continued development process, I will focus on improving enemy AI behavior by refining movement logic and implementing a proper chase system. After that, I will add health and damage systems. I also plan to duplicate the current enemy to create variations, including a larger enemy that can split into smaller ones, and potentially add a ranged or turret-style enemy for more gameplay variety.

Alpha Release:
The Alpha version of our project will be completed and pushed to the repository under the Final Alpha branch by the end of this week. 

Contributors:
  • (Lead) Sky Sin
  • Ryan Lopez
  • Alexa Baios
  • Adam Mack


Module Three Team Project Plan:
Team Update:
Originally, our team planned to work in pairs per blueprint build. However, after discussion, we decided to assign more focused individual roles to improve efficiency and reduce conflicts.

Current team roles:
  • Alexa - Player Character (movement, controls, health, and damage systems)
  • Sky - Enemy AI (movement, health, and damage systems), then will move on to jump pads and teleporters
  • Adam - UI and Map
  • Ryan - Pickups (Health, Temp. Speed Boost, and Extra Health (Shield))
  
This structure will allow each team member to focus on one core system before moving on to additional features.

Testing Plan and Schedule:
Play Test -
Testing will begin early during development as soon as core systems are implemented.
During this time, we will test:
  1. Character movement
  2. Enemy AI movement
  3. Enemy behavior

By the end of this stage, we expect to verify that the enemy can move towards the player and begin testing the basic interaction between the player and the enemy.

Demo Testing -
Before any demonstration of the project, we will test how the systems interact.
During this time, we will test:
  1. Enemy AI dealing contact damage to the player
  2. Player movement and response
  3. Initial gameplay flow between the player and enemies

The goal is to ensure the game is functional and playable for demonstration.

Code Release Testing -
During the code release stage, testing will focus on ensuring that all implemented systems meet the design expectations.
During this time, we will:
  1. Test all implemented features against the project design plan
  2. Confirm systems work together without breaking gameplay
  3. Retest previously fixed bugs to ensure they remain resolved

Weekly Testing Focus:
For this week, testing will focus on core gameplay systems:
  1. Player character functionality (movement, speed, health)
  2. One Enemy AI (Movement and contact damage)
  3. One pickup item (health, temp. speed boost, ot shield)

We will test whether the enemy correctly follows the player and applies damage on contact, and whether pickups correctly affect player attributes when collected.

Testing Checklist (Pass/Fail):
The following items will be tested and marked as pass or fail:
  1. Player movement works correctly
  2. Player health system functions
  3. Enemy AI moves correctly
  4. Enemy AI follows the player
  5. Enemy deals damage on contact
  6. Pickup activates on overlap
  7. Pickup correctly modifies player stats

Updates on the test plan:
The test plan will be updated as new features are added or the design document is changed. Each time a new system is implemented, it will be added to the testing checklist and included in future testing sessions.

Bug Reporting Method:
All bugs and issues will be reported through the team’s Discord channel. Team members will describe the issue and provide details about when and where the bug occurred.

Bug Tracking Over Time:
Once bugs are reported, the team will work together to resolve them. Progress on bug fixes will be discussed during team meetings and tracked informally through Discord communication and team updates.

Contributors:
  • (Lead) Sky Sin
  • Ryan Lopez
  • Alexa Baios
  • Adam Mack

Module Two Team Project Plan:

Scenario:
First-Person Virus Simulation -
In this project, the player is miniaturized and inserted into the human body to eliminate viruses. The player will explore a themed environment while locating and destroying virus targets.
The level will consist of a single playable level with at least five rooms of varying sizes, where the player must navigate the environment, searching for and eliminating viruses. The level will follow a consistent body-themed design.

Additional Elements Selected:
  • Jump pads to get to other areas (4; can be a simple vertical leap or a horizontal throw) 
  • Teleporters that allow the player to move quickly between certain sections of the level. (4; at least 2 pairs) 
  • Pick-ups will be placed throughout the level to assist the player. (9 total; at least 3 unique items)
    - Health Pickups
    - Ammo Pickups
    - Shield/Extra Health Pickups
  • Virus-tracking capability that helps locate virus targets within the level. This may be implemented using a directional indicator or similar tracking feature.

Brainstormed Lvl Contents:
The game level will take place inside the human body. The player has been miniaturized and inserted into the body to locate and eliminate viruses spread across different areas.

Possible room ideas:
  • Entry Point - The player spawn location where the game is explained.
  • Mouth - The player will be teleported there, and the game begins.
  • Throat - The players will go down using platforms and jump pads.
  • Stomach - A big room with most of the viruses.
  • Intestine - A long hallway-style area.
Viruses will move throughout these areas using AI behavior and will deal damage to the player through contact.

Development Timeline:

Created the following timeline based on the course schedule and project milestones:

Week 2
  • Team discussion and project planning
  • Scenario Selection
  • Brainstorming level ideas
  
Week 3
  • Begin implementing Player character and movement
  • Begin implementing Virus AI movement and damage behavior

Week 4
  • Begin implementing Jump pads
  • Begin implementing teleporters
  • Begin implementing pickups

Week 5
  • Begin level blockout
  • Create the basic five-room layout
  • Implement player spawn point

Week 6
  • Implement virus tracking/ minimap
  • Begin applying textures and environmental details

Week 7
  • Game play testing and adjustments

Week 8
  • Final polish

Alpha Stage Development Goals:
The Alpha stage will focus on creating a playable version of the level that includes the core gameplay systems.
At the Alpha stage, the following elements should be in place:
  • Player movement and shooting are working
  • Virus enemies implemented with basic AI movement
  • Virus enemies are capable of damaging the player
  • Jump pads are working correctly
  • Teleporters functioning properly
  • Pickups implemented (health, ammo, shield)
At this stage, the level should be playable, but visual polish and final mechanics may still need improvement.

Beta Stage Development Goals:
The Beta stage will focus on completing gameplay systems and improving the level's overall quality.
The following elements should be implemented during the Beta stage:
  • Fully playable level
  • Fully textured environment
  • Gameplay balancing and bug fixes completed
The Beta version should represent a nearly finished version of the level.

Communication Methods:
  • Discord for messaging, team discussions, and video/voice meetings when needed.
  • GitHub repository for project files, documentation, and version control
These tools will allow the team to communicate efficiently and track project progress.

Team Meeting Frequency:
The team will meet at least once (twice preferred) per week to review progress, discuss tasks, and plan upcoming work. Additional communication will occur through Discord if questions or issues arise between meetings.

Task Assignment and Progress Reporting:
Tasks will be assigned and tracked using GitHub Issues or a project management tool within the repository. Each team member will be responsible for completing their assigned tasks and reporting progress during team meetings.

This method allows the team to track work progress and ensure responsibilities are clearly defined.

Contributors:
  • Sky Sin
  • Ryan Lopez
  • Alexa Bairos
  • Adam Mack
  • 
