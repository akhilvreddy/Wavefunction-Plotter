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


## The simplest case: Particle in a box (V=0)
For these cases, the wavefunction isn't too difficult to derive. I skipped coding this step but you can see how the wavefunction behaves from looking at this gif from Wikipedia: 
<p align="center">
  <img 
    width="200"
    height="187"
    src="https://github.com/akhilvreddy/Wavefunction-Analysis/blob/main/200px-InfiniteSquareWellAnimation.gif"
  >
</p>

## The Code
All of my code can be found [here](https://github.com/akhilvreddy/Quantum-Wavefunction-Analysis/blob/main/WavefunctionNotebook.ipynb). 

## Particle in a varying potential 
For this case, I came up with a special type of potential function, which was more of like a upward facing parabola, but was completely under the x-axis the whole time. This way, the potential barrier was still a well. This is what the potential looked like: 

<p align="center">
  <img 
    width="390"
    height="187"
    src="https://github.com/akhilvreddy/Quantum-Wavefunction-Analysis/blob/main/wavepotential.png"
  >
</p>

# The Solution 
In my code, I highlighted two ways that this could be solved. They both ended up giving me the same asnwer, and I was able to make an animation of the evolution of the wavefunction against time. Here is what it looked like: 

<p align="center">
  <img 
    width="700"
    height="430"
    src="https://github.com/akhilvreddy/Quantum-Wavefunction-Analysis/blob/main/Pictures/pen.gif"
  >
</p>

## The Hydrogen Atom
This is the part that I am still working on. There are a lot more things to consider here, like spherical harmonics and solving multiple different differential equations, for the radial and angular parts. 
