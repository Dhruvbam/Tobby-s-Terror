# Toby's Terror
<p align="center">
  <img src="https://github.com/Dhruvbam/Tobby-s-Terror/blob/main/Images/tt.png" alt="Toby's Terror" />
</p>


Toby's Terror is an interactive horror video game developed by Team Skynet Dev Club for the Introduction to Artificial Intelligence class at Texas Tech University. Developed using Unity, the game challenges players to outmaneuver Toby, a relentlessly adaptive, AI driven enemy NPC. Toby’s advanced behavioral logic is powered by Finite State Machines, Unity’s NavMesh, and custom raycasting systems, enabling him to patrol, chase, and react dynamically to player movement within a modular, richly detailed 3D environment. This project demonstrates both theoretical understanding and practical application of AI techniques in gaming, teamwork and project management, and a commitment to delivering polished gameplay for modern consumer hardware.

## Built With
- <a href="https://unity.com/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white" width="36" height="36" alt="Unity" /></a> **Unity**: The game engine used for development.
- <a href="https://learn.microsoft.com/en-us/dotnet/csharp/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/csharp-colored.svg" width="36" height="36" alt="C#" /></a> **C#**: The programming language for scripting the game's logic.
- **Finite State Machine (FSM)**: The architecture used to control Toby's AI behavior.
- **Navigation Mesh (NavMesh)**: Used for pathfinding in the game's dynamic environment.
- **Raycasting**: Implemented to improve Toby's navigation and prevent getting stuck in obstacles.

## Features & Technical Details

- **AI-Driven Enemy:** Toby’s behavior is powered by a Finite State Machine (FSM), allowing for fluid transitions between patrol, chase, and search states. This creates unpredictable gameplay and elevates replay value for players.
- **Real-Time Pathfinding:** The NavMesh system enables Toby to traverse complex environments with \(O(\log n)\) computational efficiency, reliably chasing players and reacting to changes in the map.
- **Raycasting Logic:** NPC maintains spatial awareness and obstacle avoidance through continuous raycasting, preventing pathfinding failures and enhancing immersion.
- **Scalable Performance:** The project is designed for optimal runtime efficiency and modularity, with core gameplay loops executed in C# and Unity handling asset management and rendering.
- **Professional Asset Integration:** Modular First Person Controller and POLYGON Dungeons assets were used for rapid development and AAA-quality visuals.
- **Team Collaboration:** Developed by a talented team of four, showcasing advanced planning, version control (GitHub), and distributed development practices in a real-world project.
- **Complexity Stats:**
  - FSM decisions: \(O(n)\) per update cycle
  - NavMesh lookups: \(O(\log n)\) by environment size
  - Game runtime optimized for smooth experience on consumer hardware

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/tobys-terror.git
    ```
2. Open the project in Unity.
3. Ensure all necessary packages are installed via Unity Asset Store:
    - Modular First Person Controller
    - POLYGON Dungeons
4. Build and run the game from Unity.

## Contributions / References
This project was a collaborative effort by the members of **Team Skynet Dev Club**:
- **Dhruv Maniar**
- **Hunter King**
- **Taylor Dobson**
- **Sebastian Baglo**

References:
- Sindhu, R. M., et al. "Development of a 2D Game using Artificial Intelligence in Unity." *2022 6th International Conference on Trends in Electronics and Informatics (ICOEI)*, 2022, pp. 1031-1037.
- Toll, Wouter G. van, et al. “A Navigation Mesh for Dynamic Environments.” *Computer Animation and Virtual Worlds*, vol. 23, no. 6, Wiley, June 2012, pp. 535–46.

## Screenshots / Demo
![Toby's Terror](https://github.com/Dhruvbam/Tobby-s-Terror/blob/main/Images/tt.png)
<br/>
![Screenshot 1](https://github.com/Dhruvbam/Tobby-s-Terror/blob/main/Images/tt.jpg)
<br/>
[Watch the video](https://github.com/Dhruvbam/Tobby-s-Terror/blob/main/Images/AIPres2Demo1.mp4)

