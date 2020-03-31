# Coupled Tanks Lab

This is a simulation created for a fluid dynamics lab. It is offered as a proof of concept more than anything, showing how D3 can be used to visualize a set of equations.

In both of these, the slider at the bottom can be used to govern the speed of the sinusoidal input tank, and the sliders to the right hand side govern the size of the 'tube' leading from one tank to the other.

the small tanks can be thought of as a star pattern, with each of the small tanks in a circle around the large one. Each of the small tanks have a 'tube' that connect it to the ones beside it on the outside ring, and each small tank as a tube linking to the main oscillation tank. 

The size of each of these tubes can be modified.

I currently have the following:

* [Test](https://w4kpm.github.io/CoupledTanks/test.html) - this has uniform small tank size and the inductance of the tubes is not accounted for.
* [TestInduct](https://w4kpm.github.io/CoupledTanks/testInduct.html) - this has different sized small tanks and the inductance of the tubes is accounted for.
* [FluidLab](https:\\w4kpm.github.io\CoupledTanks\Fluid%20Lab.pdf) - a set of notes about the equations used for calculating fluid flow in each of the tubes and tanks.

