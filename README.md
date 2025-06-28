# Diffusion Model
A model allowing for the simulation of diffusion and effusion at the particulate level.
## WHAT IS IT?
This model demonstrates the behavior of gases during diffusion and the process of reaching a dynamic equilibrium.

## HOW IT WORKS
The particles are programed to bounce off of each other and off of the walls and barrier. If two particles collide, both particles will turn around 180 degrees and continue at the same speed that they initially had. A particle that hits a wall or the barrier collide in the same manner.

## HOW TO USE IT
**SETUP:** clicking the setup button will setup the world based on the parameters the user sets using the sliders (how many turtles on each side, how many slits, width of slits, etc).

**GO:** causes the turtles to move, following the rules for collisions.

**SHOW-DIRECTION?:** Changes the shape of the particles. If yes, particles are shown as arrows so that their direction or heading can be seen. If no, particles appear as dots.

**SHOW-PATH?:** If yes, particles leave a trail as they move so that you can follow their movement and collisions over time. If no, particles just move without leaving a trail.

**CLEAR PATHS:** Erases all of the paths drawn when the button is pressed. If Show-path? is yes, new paths will be drawn as soon as the paths are cleared.

**NUMBER-OF-PARTICLES-ON-LEFT (SLIDER):** Determines the amount of particles that begin on the left side of the barrier. These particles are blue.

**NUMBER-OF-PARTICLES-ON-RIGHT (SLIDER):** Determines the amount of particles that begin on the right side of the barrier. These particles are orange.

**BARRIER?:** If yes, a barrier between the right and left sides will form according to the slit settings below. If no, no barrier will be created, regardless of the slit settings.

**NUMBER-OF-SLITS:** When a barrier exists, this determines the number of slits in the yellow barrier through which the particles can pass.

**WIDTH-OF-SLITS:** When a barrier exists, this determines the width of each slit in the yellow barrier.

**TEMPERATURE:** Determines the temperature of the system and hence of the particles.

**PARTICLES ON LEFT (COUNT):** Displays the total number of particles on the left side of the barrier at any given point in time.

**PARTICLES ON RIGHT (COUNT):** Displays the total number of particles on the right side of the barrier at any given point in time.

**STOP-AT-EQUILIBRIUM?:** Stops the particles from moving (stops the model) once the number of particles on the left equals the number of particles on the right.

**NUMBER OF PARTICLES VS TIME (GRAPH):** Graphs the number of particles on each side against time as the model runs. The number of particles that are on the left are marked by a yellow line while those on the right are marked by a magenta line.

## THINGS TO TRY AND TO NOTICE
Set barrier? to yes and the number of slits to 0 and see how the particles act when confined to one side.

Set barrier? to no. Notice how the particles act when there is no barrier.

Change the number of particles that begin on each side. Notice how this effects the diffusion of the particles.

Set barrier? to yes. Change the number of slits and notice how this affects diffusion. Change the width of the slits and notice how this affects diffusion.

Try running the model with different temperatures. What effect does temperature have on the particles?

Notice the behavior of the particles over time using the graph and the counts on the right side of the model. Compare graphs from different trials where different variables from above were changed. In what way does each variable affect the rate of diffusion?

## EXTENDING THE MODEL
This model could take into account the transfer of energy when particles collide. Instead of maintaining the same energyand speed and merely reversing direction, particles can be set to have collisions that are not head-on.

Pressure could be added to this model using the number of collisions on the walls. With temperature, pressure, and number of molecules, the ideal gas law could then be demonstrated with just the addition of volume. To change the volume on either side, the barrier could be shifted left or right or be made thicker.

Turtles (Particles) of different sizes could be introduced to show the effects of a semi-permeable membrane where small particles can pass through the barrier while larger ones can not. The width of the slits would play an even bigger role in such a model.

## RELATED MODELS
GasLab Models Heat Models Connected Chemistry Models

## CREDITS AND REFERENCES
This model was created by Courtney Luckabaugh Ward.