### A WebGL Flight Simulator
A Computer Graphics Group Project

# To run:
Clone the repository and open flightsim.html in a browser (chrome & firefox are supported).

# Controls
You can control the speed of your plan with the W and S keys.  You can control the yaw of your plane with the A and D keys.  You can control the pitch of your plane with the up and down arrow keys.  You can control the roll of your plane with the left and right arrow keys.

# Efficiency
We implemented the following code efficiency:

## Terrain Generation
We manage to make our load time per chunk relatively low using the speed efficient perlin function to generate our height.

## Chunk Saving
We were able to cut down more time by saving chunks we have previously for when we come back to them.

# Bonus
We implemented the following bonus functionalities:

## Skybox
We implemented a basic skybox that gives the world a more natural look, instead of the white or black background it typically is.  This also allows us to adjust the 'render distance' of our simulator, as we can grow or shrink the skybox.

## Smooth terrain
Due to our use of perlin noise, we were able to achieve terrain smoothness, where there are no jagged jumps or valleys, but isntead a single continuous smooth look.

## Fog
We implemented a fog effect which, when turned up slightly, can hide the generation of far away chunks.
