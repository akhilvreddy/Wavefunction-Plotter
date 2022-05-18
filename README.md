# Quantum Wavefunction Analysis
Generated and plotted quantum wavefunctions for single particles, particels in potential wells, and currently working on spherical harmonics for the hydrogen atom.

## Abstract 
The motivation behind this project was to have a clear visualization of the real, imaginary, and squared probabilistic verison of the wavefunctions. In my opinion, Griffith's did not provide many clear images of this and on paper there is no way to see them move. In this project, I aim to generate wavefunctions that oscillate in time and space. I also added potential constraints. The final part is working with the spherical harmonics of the hydrogren atom, which I find to be a little difficult. 

## The math & physics behind a wavefunction
<p align="center">
  <img 
    width="544"
    height="128"
    src="https://github.com/akhilvreddy/Wavefunction-Analysis/blob/main/version1.png"
  >
</p>

> Ψ is the wavefunction. ℏ is the reduced Planck's constant. m refers to the mass of a particle. V is the potential & E is the total energy. 

Even if you haven't seen this equation before, you have probably heard of it - it is called _Schrodinger's Equation_. This equation is a Partial Differential Equation and this specific one is solved by using a technique called separation of variables. In the equation, the first term represents the Kinetic Energy of the particle, the second term represents the Potential Energy of the partcile (V for potential as you have probably seen before) and the term on the right hand side represents the total energy of the particle. 

Here, Ψ is the wavefunction and by taking the square of it's magnitude, it gives us the probability density of where we expect the particle to be. The higher the amplitude, the higher the chance the particle can be found there, and vice versa. Below, I have written code for both Ψ and the square magnitude of Ψ. I started off simple by setting the potential equal to 0 and slowly added more. 

## Writing the python code

### Issues I ran into - 
- deez
- nuts


## The simplest case: Particle in a box (V=0)
<p align="center">
  <img 
    width="200"
    height="187"
    src="https://github.com/akhilvreddy/Wavefunction-Analysis/blob/main/200px-InfiniteSquareWellAnimation.gif"
  >
</p>

## Particle in a constant Potential

## The Hydrogen Atom

## Sources
 - Griffith's Intro to Quantum Mechanics
 - Wikipedia



