# Final-DSCI-100-Project
Background
Recruiting and retaining active users is critical for running online gaming experiments. The UBC Minecraft research server, led by Prof. Frank Wood, offers an open-access environment in which every movement and click are automatically logged. While the server generates rich behavioural data, only a small fraction of players eventually subscribe to the project’s game-related newsletter—a low-cost channel for announcing new experiments, updates, and funding opportunities. Being able to predict subscription likelihood from readily available player attributes would allow the team to focus recruitment messages on users most likely to engage, thereby increasing subscription rates without expanding marketing effort.

Primary Question
Can a player’s experience level, playing time, and age predict whether a player subscribes to the game-related newsletter?
Datasets
Two CSV files are provided and are linkable via the primary key player_id.
1. players.csv – one row per unique participant.
2. sessions.csv – one row per play session; multiple sessions per player.
After importing, the merged file contains 1,842 players and 9,407 sessions collected between 2024-08-01 and 2024-11-30.
