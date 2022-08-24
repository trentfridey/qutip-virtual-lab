QuTiP Virtual Lab
=================
_[source](https://github.com/qutip/qutip/wiki/Google-Summer-of-Code-2022#qutip-virtual-lab)_


Simulating quantum physics in QuTiP provides an excellent educational tool. However, using QuTiP requires writing Python code, which may present an obstacle in some teaching contexts. Programming is, of course, a very valuable skill to master. Attempting to master it while simultaneously coming to grips with quantum mechanics is perhaps less advisable.

We would like to create a graphical virtual laboratory powered by QuTiP which allows users to explore quantum systems without being distracted by the need to write software.

The virtual lab would allow building up experiments from components (e.g. sub-spaces such as qubits, Hamiltonians for those subspaces, interaction Hamiltonians, environment baths), evolving the system over time, applying measurements, and attaching monitoring of quantum states or measurement outcomes (e.g. Hinton plots, Bloch sphere plots).

We'd like the laboratory to have a beautiful user interface and to support tablets and smartphones eventually, thus Kivy or Godot look like good libraries to build the interface with.

Project size:

    350 hours

Difficulty:

    Hard

Deliverables:

    A graphical interface that acts as a virtual laboratory
    Allows the construction of simple quantum systems (e.g. placing four neutral atoms)
    Allows defining the evolution of each system component
    Allows defining the interactions between system components
    Allows coupling the system to an environment bath
    Allows simulating the system dynamics and visualizing their evolution over time
    Allows visualizing the steady state of the defined system
    Can be run on both desktop and tablets

Skills:

    Familiar with Python and numpy
    Familiar with Git
    Familiar with or keen to learn Kivy or Godot
    Really excited about building a virtual laboratory!

Mentors:

    Alex Pitchford (alex.pitchford@gmail.com)
    Simon Cross (hodgestar@gmail.com)
