Key to the Kingdom – Java RPG Game

Key to the Kingdom is a Java-based role-playing adventure game developed for COMP3663 (Software Engineering 2). The player explores multiple regions, interacts with NPCs, collects items, and must retrieve the Legendary Key from the Cave and return it to the Queen.

The game is built entirely in Java + Swing, featuring a multi-threaded engine, event-driven systems, dynamic audio, collision detection, and an interconnected world.

🎮 How to Run

Install Java 8 or higher
Open the project folder in VS Code, IntelliJ, Eclipse, etc.
Run the main file:

RPG.java

🗺️ Game Features

Four explorable areas (Castle, Field, Cave, Village)
NPC interactions and dialogues
Inventory and item system
Randomized key placement
Collision-based movement
Quest completion system
Dynamic audio themes for each area

⚙️ Technical Highlights

Java + Swing GUI
Multi-threaded game loop (50 FPS target)
Double-buffered rendering
Chunk-based map loading
Event-driven architecture (doors, triggers, NPCs, items)
Resource Manager with caching & LRU eviction

Modular systems:
Character System
Map System
Event System
Audio System
UI System

🧪 Testing

Unit testing (movement, collision, inventory)
Integration testing
System testing
Performance testing (stable 50 FPS)
Audio and UI testing

🏆 Achievements

Stable performance across all areas
Smooth movement and animation
Efficient resource management
Fully documented development lifecycle
