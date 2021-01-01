# ExploringQC⚛

A uncool approach to learn the dark arts of quantum computing [__Just Logs of what I am upto or mess up__]

### Short term goals:
<p align = "center"><img src = "https://media.giphy.com/media/daasWol3l8f155ITtr/giphy.gif" height = 50% width = 50%></p>

- Grasp the math ahead of the foundations
- Key Terminologies
- Relate to high school physics days
- Take psuedo inspiration from Neil DeGrasse Tyson
- Learn QisKit
- Build cute projects. Quite a lot that one can fill the resume with but after a month won't be worth it
- Understand why on earth do we need QuantumML? 
- Or QuantumCV?
- Revise basics of applied cryptography
- TensorFlowQuantum
- Use IBM and DWave Systems
- Build an end to end project
- Teach 5 people 
- Be satisfied enough to add Quantum Computing as a skill on LinkedIN
- Quantum Open Source

## Resources:

1. Quantum Computing: An Applied Approach by Jack D. Hidary 

```
@book{hidary2019quantum,
  title={Quantum Computing: An Applied Approach},
  author={Hidary, Jack D},
  year={2019},
  publisher={Springer}
}
```

### Day 1:

- How do we understand Quantum Computing?
- What does Quantum Mechanics say about the state of a system?
     - Revisit: Schodinger's cat
- What is superposition 
   - What is linear combination
- Example of superposition: Polariation of light (when we use a polarization filter, there is superposition of the horizontal and vertical state of the movement of Electric field)
   - Revisit: Wave Theory Fundamentals:
        1. What is a wave?
        2. Crest(Highest point) and Trough(Lowest point)
        3. Amplitude --> `vertical distance between the tip of a crest and the wave’s central axis is known as its amplitude`
        4. Wavelength --> `The horizontal distance between two consecutive troughs or crests`
        5. Frequency --> `the number of full wavelengths that pass by a given point in space every second`
        6. Relationship between wavelength and frequency of a wave: `the shorter the wavelength, the higher the frequency, and vice versa`
        7. Period of a wave --> `the length of time it takes for one wavelength to pass by a given point in space.`
        8. Electromagnetic Spectrum
        9. Plank's theory of blackbody radiaton
        10. Photon
        11. Interaction between atoms in term of Photons
        12. Maxwell's Experiment
    - What is polarized light?
    - Polarization
    - Types of Polarization
    - Real life uses
- An extended case of the above:
     1. Case A: the first filter is horizontal, second is vertical, what light do you see?
     2. Case B: the first filter is horizontal, second is vertical, what light do you see
- Born's rule --> `the modulus square of the amplitude of a state is equal to the probability of its' occurence after measurement`
- EPR (Einstein Pdolsky Rosen) Paradox
- Weird concept of entanglement, "spooky action at a distance"
- Interpretation in information theory
- Physical limitation of the speed and compactness of computing circuit in terms of energy dissipated --> Launderer Bound
- Relation with Moore' Law
- Irreversibility ( base definition in terms of information theory) --> `If the output cannot explicitly define the input of the system`
     - Revisit Second Law of Thermodynamics
           - Revisit Entropy
           - Revisit First Law of Thermodynamics
- Classical Computing Irreversible Operation example (Simply an OR/AND GATE)
- Quantum Computers should have reversible logical information --> No measurement is lost implying no information is lost
- Convert Irrevesible Computers into Reversible

###### Resources:

Superposition
  - [Schrodinger's Cat explanation by minutephysics](https://www.youtube.com/watch?v=IOYyCHGWJq4) - Watch till 1:18
  - [Understanding Quantum Mechanics #2: Superposition and Entanglement](https://www.youtube.com/watch?v=j6Mw3_tOcNI) - Watch till 2:10
  
Wave Theory Fundamentals: 
    - [Khan Academy Blog](https://www.khanacademy.org/science/physics/light-waves/introduction-to-light-waves/a/light-and-the-electromagnetic-spectrum)
    - [Khan Academy's Explanation Maxwell's Experiment](https://www.khanacademy.org/science/physics/light-waves/introduction-to-light-waves/v/electromagnetic-waves-and-the-electromagnetic-spectrum)

Polarization: [Khan Academy's Explanation](https://www.khanacademy.org/science/physics/light-waves/introduction-to-light-waves/v/polarization-of-light-linear-and-circular)

Born's Rule
     - [Explanation by Looking Glass Universe](https://www.youtube.com/watch?v=VHlqY44fOg0)

EPR Paradox + Quantum Entanglement:
- [Frank Wilzek's article on the Quanta Magazine Blog](https://www.quantamagazine.org/entanglement-made-simple-20160428/) ** CS folks can enjoy this solely
- [Video 1](https://www.youtube.com/watch?v=fBR5HQ-Ja10), [Video 2](https://www.youtube.com/watch?v=-WSWz1H3mJg) - Parth's explanations on YouTube (for our folks who wanna learn this the fun high school physics related jargon way]

Launderer principle, Irreversiblity of Computation, Reversible Computers
  - [Lecture by Holger Bock Axelsen](https://www.youtube.com/watch?v=rVmZTGeIwnc)
