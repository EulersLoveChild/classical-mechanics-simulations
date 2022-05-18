# Classical Mechanics Simulations

Below, I document some physics simulations that fall under classical mechanics. This was done using Newtonian, Lagrangian, and Hamiltonian mechanics. 

**The angles were measured from the vertical down.

**The positions of masses attached to springs was measured as the distance from the equilibrium positions.

**Angles and positions were randomized to diversify the simulation.

**Each simulation below (except N-Body) has two plots: y vs x and x vs t. The former is more visual and shows (and updates) the positions of each object along with side objects (which are taken to be massless), like springs and strings. The latter plot shows how the position changes (of objects with mass) with respect to time and is a simple scatterplot.

**In the formor plots, springs are always gray and strings are always black. Objects with mass are any color but those. The transparent circles of these graphs are the initial position of each of the objects with mass and are given just as a way to visually compare intial vs final positions of the system.

**In the latter plots, the colors of the objects with mass are the same as their colors from the first plot. 

## 1) Pendulum on an Oscillating Mass

[![MSP](https://i.imgur.com/O5choAa.png)]
 
In this experiment, I simulate a pendulum attached to a mass. This mass is attached to a spring, which is attached to a wall. Note that this was made with Hamiltonian Mechanics and does in fact use the small angle approximation of cos(x) = 1 - x^2/2;

## 2) Double Pendulum

In this experiment, I simulate a pendulum attached to another pendulum. The acceleration components were constructed with the Lagrangian. In addition, I use a small angle approximation for both pendulums. 

## 3) Two Masses and Three Springs

In this experiment, I simulate two masses, with a spring between them, a spring between the first mass and a wall on the left, and a spring between the second mass and a wall to the right. Note that the acceleration compenents were obtained from Newtonian Mechanics.

## 4) Three Oscillating Pendulums with Springs

In this experiment, I simulate three pendulums with springs between the 1st and 2nd, and the 2nd and 3rd. This was done with the help of Lagrangian Mechanics and so, the small angle aproximation was used for all three angles.

## 5) N-Body Simulation (simple) 

In this experiment, I simulate particles and their trajectories based on gravity. These particles are supposed to represent black-hole-like objects so a "black hole" can absorb another "black hole" when the one enters the other's event horizon. Obviously, this is a oversimplification of real life black hole mergers, but this is a decent simulation of what happens to these unrelatavistic objects.