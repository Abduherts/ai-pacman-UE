This repository contains the initial C# implementation of the AI-Powered Pac-Man project core requirements.

## Features
- **Core Data Structures**: Implementation of `Vector2Int`, `GameState`, and `GameStatePhase`.
- **Grid Management**: `GridManager` for maze representation and neighbor detection.
- **Pathfinding**: Fully functional **A* (A-Star)** algorithm with Manhattan distance heuristic.
- **Pac-Man AI**: Basic state-based decision making (Chasing Pellets and Fleeing from Ghosts).
- **Ghost AI**: Initial pursuit logic for different ghost personalities (Aggressive, Interceptor, Defensive).

## Project Structure
- `src/Core.cs`: Basic game state and utility structures.
- `src/GridManager.cs`: Maze logic and A* pathfinding implementation.
- `src/PacmanAgent.cs`: Pac-Man's decision-making logic.
- `src/GhostAgent.cs`: Ghost pursuit and behavior logic.
- `src/PacManAI.csproj`: Project configuration file.
