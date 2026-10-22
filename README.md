## Prerequisites and Setup
In this project is used:
1. Unreal Engine 4.26
    - Download Epic Games Launcher
    - In the launcher go to the Unreal Engine and install the version 4.26
2. Git and Git LFS

## How to import the project
Open the terminal and clone the repository, this is the command:
```bash
git clone https://github.com/BrunelloLuca/eagle_simulation
```

# Test the task
## Task 1
- I imported a Formula Student-style vehicle mesh and merged into `formulaMerged`
- For the track I create it with spline mesh and then I duplicate the blueprint of it to add the cones.

## Task 2
- I use the Wheeled Vehicle system and I add it the imported Formula Student-style mesh.
- To test it you have to press Play and you drive it using `WASD`.

## Task 3
To implement the LiDAR sensor:
- I have modified the `VehicleBlueprint` in `VehicleAdvBP`.
-  I have added a `Scene Component` on a front
-  Create a function `Sim Lidar` to simulate the 2D LiDAR using raycasting