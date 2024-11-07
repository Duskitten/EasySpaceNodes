# Godot_SpaceNodes
Godot helper nodes to create 2D/3D Spaces for physics automatically.

## Why?

This is useful in the event you would like to have many scenes with overlapping objects that may not want to interact with eachother and you don't want to waste physics layers

Example: 

Server-side maps with characters moving on it, can all be centered at (0,0) and never interact with eachother ever, leading to more optimized performance than relying on viewport method.

## How to Use:
1. Add a PhysicsSpace2D/PhysicsSpace3D to your scene

2. Place wanted physics nodes underneath (It will auto filter for you)

3. Profit
