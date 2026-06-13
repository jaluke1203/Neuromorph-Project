# Neuromorphic Project

**Overview:** This Project was completed in ECE 576, Neuromorph Engineering, at the University of Massachusetts Amherst. I worked on this project with two great partners Parth Goel, and Ryan Dandrea. Our goal was to emulate an event camera through video processing and then use the emulated video to train an SNN (Spiking Neural Network) to recognize hand gestures in the videos ran through the emulator. We did not want to just emulate the event camera through software we also wanted to prove that our software emulation was suported by actual hardware behavior. This was done through circuit simulation using LTspice that represents the behavior of a pixel in an event camera and then running the pixels of videos through the LTspice circuit collecting the circuit response to show that our software emulation and simulated hardware emulation agreed with eachother.

## Roles
- **Jacob (me):** Simulated hardware circuit design and verification, Simulated hardware emulation and software emulation accuracy validation
- **Ryan:** Software Emulation
- **Parth:** SNN model tranining and design, Training dataset creation
