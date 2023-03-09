# VizDoom-Reinforcement-Learning-Model

Reinforcement Learning / CNN model trained to play Doom within the VizDoom gym environment, for a variety of scenarios and complexities.

## VizDoom Scenarios:
### Basic
Trained to defeat a single unmoving enemy
Can only move left, move right, and shoot ( more controls implemented later )
Reward based on if opponent was succesfully shot, and how fast/efficienct was this

### Deadly Corridor
Trained to navigate a corridor with multiple attacking enemies
Reward based on amount of damage taken and how fast level was completed

### Defend the Center
Trained to defend the cenet of a room with enemies coming at all angles
Reward based on how long the model can last in the center
