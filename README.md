# Pokémon-Themed RPG Game
=======================

A text-based RPG game developed in Java where players battle Pokémon with different types like Fire, Grass, and Water. This project demonstrates the use of object-oriented programming and design patterns to create a dynamic and interactive gameplay experience.

## Features
--------

-   **Battle Mechanics**: Engage in battles with Pokémon of various types, including Fire, Grass, and Water.
-   **Power-Ups**: Boost attack and health points using `AttackUp`, `AttackDown`, `HpUp`, and `HpDown` classes.
-   **Map Navigation**: Navigate through different areas in the game using a map and coordinate system.
-   **Decorator Pattern**: Add abilities to Pokémon dynamically during gameplay with the `PokemonDecorator` class.
-   **External Data Integration**: Load Pokémon and area data from external `.txt` files for a customizable experience.

## Technologies Used
-----------------

-   **Java**
-   **Object-Oriented Programming**
-   **File I/O** (handling `.txt` data files)
-   **Design Patterns** (Decorator Pattern)

## How to Play
-----------

1.  **Clone the Repository**\
    Clone the repository to your local machine:

    `git clone [repository-url]`

2.  **Compile the Java Files**\
    Open a terminal, navigate to the project directory, and compile the Java files:

    `javac *.java`

3.  **Run the Game**\
    After compiling, run the main class:

    `java Main`

    This will start the game, allowing players to interact with Pokémon, explore areas, and engage in battles.

File Structure
--------------

-   **Main.java**: Entry point for the game, containing the main game loop.
-   **Pokemon.java, Trainer.java**: Core classes for Pokémon and player entities.
-   **AttackUp.java, AttackDown.java, HpUp.java, HpDown.java**: Manage attack and health boosts.
-   **Fire.java, Grass.java, Water.java**: Define Pokémon types with unique attributes.
-   **PokemonDecorator.java**: Implements the Decorator Pattern to dynamically add abilities to Pokémon.
-   **Area1.txt, Area2.txt, Area3.txt**: Map data for different areas within the game.
-   **PokemonList.txt**: List of Pokémon and their attributes used to generate opponents.
