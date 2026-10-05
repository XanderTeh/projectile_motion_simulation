# projectile_motion_simulation
This project investigated projectile motion under ideal conditions and with linear and quadratic air resistance

This project investigates the motion of the motion of a projectile using mathematical modelling and numerical simulation. Projectile motion is the curved path an object follows when it is launched into the air and moves under the influence of gravity, and subsequently air resistance/drag. The project begins with an ideal system in which the projectile is only moving under the influence of gravity, and later progressively introduces drag to investigate its effect on the motion.

The projectile motion was simulated under increasingly realistic models of air resistance. The ideal model was solved analytically. Introducing air resistance produces substantially different trajectories, along with some drastically more complex differential equations describing the projectile. The linear drag model was solved analytically where possible, and quadratic drag model was solved numerically.

For the parameters used, the ideal projectile achieved a range of $91.7\mathrm{m}$, compared with $47.3\mathrm{m}$ for linear drag and $55.9\mathrm{m}$ for quadratic drag. Air resistance also changed the launch angle that maximises range, from $45^\circ$ in the ideal case to $36.1^\circ$ for linear drag and $40.8^\circ$ for quadratic drag.

Euler's method was used to numerically solve the equations of motion for the drag models where they cannot be solved analytically. This method provides a simple approach when analytical solutions become difficult or unavailable, although its accuracy depends on the chosen time step. The project also considered terminal velocity and Reynolds number to connect the mathematical models with their physical interpretation.

Overall, the project demonstrates how a simple analytical model can be extended using numerical methods to investigate increasingly realistic physical systems.

References:

https://discovery.ucl.ac.uk/id/eprint/10073838/1/Eames_Klettner_.pdf

https://www.physics.udel.edu/~szalewic/teach/419/cm08ln_quad-drag.pdf

https://en.wikipedia.org/wiki/Projectile_motion

https://en.wikipedia.org/wiki/Reynolds_number

https://en.wikipedia.org/wiki/Terminal_velocity
