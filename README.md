Name: SHIVAM KAPOOR
Company: CODTECH IT SOLUTIONS
ID: CT08DS8658
Domain: C++ PROGRAMMING
Duration: OCTOBER 5th, 2024 to NOVEMBER 5th, 2024
Mentor: Neela Santhosh Kumar

Overview of the Project

Task1: GAME DEVELOPMENT
Create a simple game using C++, such as a text-based adventure or a graphical game using a library like SFML or SDL. The game should include core mechanics, player input, and scoring.

Project Overview: Dungeon Adventure Game

Objectives: 
1.Game Design: Develop a simple text-based dungeon adventure game where the player explores different paths, battles monsters, collects treasures, and can find items like a sword to enhance their abilities.
2.Player Interaction: Provide meaningful player choices (e.g., attacking, running, or moving in different directions) and simulate dynamic scenarios.
3.Random Events: Integrate randomness in enemy encounters, treasure discoveries, and game progression to make each playthrough unique.
4.Score Tracking: Maintain and display the player's health, score, and status of equipped items throughout the game.

Key Activities:
1.Player Exploration: The player can choose to explore in different directions (left, right, forward, or backward), triggering different random events.
2.Monster Battles: Random encounters with monsters where the player can choose to fight or run away. If fighting, damage dealt is based on whether the player has a sword.
3.Item Collection: The player can find treasure to increase their score or a sword to deal extra damage in battles.
4.Player Status Display: The game consistently updates the player on their current health, score, and whether they possess a sword.
5.Game End: The game ends when the player’s health drops to zero, with their final score displayed.

Technologies Used:
1.C++ Programming Language: The entire game logic is implemented in C++ using fundamental programming concepts.
2.Standard Libraries:
->iostream: For input and output functionality.
->cstdlib: To generate random numbers and manage dynamic behavior in events.
->ctime: For seeding the random number generator with the current time.
3.Randomization: rand() and srand() are used to ensure random encounters, treasure values, and combat damage.

Key Insights:
1.Randomness Enhances Engagement: Using random values to determine monster health, treasure points, and damage adds unpredictability, making each game session feel different.
2.Item Mechanics: Finding the sword increases the player's attack damage, introducing the concept of power-ups and enhancing combat strategy.
3.Player Choices Matter: Allowing players to choose their actions (fight or flee, explore different directions) adds an element of decision-making, which influences their survival and final score.
4.Simple Game Loop Structure: The main game loop efficiently manages player actions and interactions with the dungeon, making it easy to extend or modify gameplay.
5.Interactive Status Updates: Displaying real-time player health, score, and item status provides feedback, keeping the player informed and engaged with the game.
