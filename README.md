# Planet Simulation
Python-based 2D-simulation, which shows the closest planets orbiting the sun. Using pygame in Python we can simulate orbiting planets using their astronomical values, such as their mass, radius, their attraction to each other, and various other aspects.

# Setup and Dependencies
- The simulation requires the Pygame library, which provides tools for 2D graphics.
- Ensure Pygame is installed ```pip install pygame```.
# How does it work?
**Initialization**: The simulation initializes by creating a window with a specified width and height.
- **Planets**: Several planets are instantiated with their initial positions, velocities, radii, colors, and masses. The planets are added to a list. You can change and add planets easily by creating new instances of the simulation.
- **Planet** class with appropriate parameters.
- **Main Loop**: The main loop of the simulation starts. Inside this loop:
The clock is used to control the frame rate.
Events are checked, such as quitting the simulation.
- **For each planet**:
The **update_position** method is called, which calculates the gravitational forces acting on the planet due to other planets and updates its position.
The **draw** method is called to render the planet on the window.
The display is updated to reflect the changes.
- **Exit**: The simulation ends when the window is closed.
