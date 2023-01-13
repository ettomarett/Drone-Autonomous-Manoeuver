# Drone-Autonomous-Manoeuver

This is a project I've been working on since 2021, at first it started off as a transient college-prep school project but then I discovered my passion towards machine learning and deep learning, thus I decided to take the work further and improve this little project as much as I possibly can. I'm going to push my project at its latest stable version into this remote repository, and I'm going to be committing improvement changes and updates to it until the performance of the drone is satisfying. 

The drone is intended to be autonomous as the title implies; With a bit more details, the idea was to create a real drone, with its hardware and software, that can take the trash out and come back home automatically with no remote control whatsoever. But it's a very complicated and complex objective, that's why it was split to different parts, that once achieved, will lead to the accomplishment of the ultimate objective. Here are the parts in brief and in order :

+1. Create a world of simulation that mimics the real world and its circumstances, with all the possible physical constraints.\
+2. Create a quadcopter drone model imitating the functionalities of a real drone, including all the technical details such as : the motors, propellers and the PID controller. And let it be controllable by a game controller, or just the keyboard, for now.\
+3. Implement the right machine learning algorithm that is capable of making the drone able to learn how to accomplish the mission of arriving to a desired given location autonomously.\
+4. Once the drone is well trained in the simulation world, we can take the trained model's brain which is the ONNX file and load it into the microprocessor of the real drone, whether it's a Raspberry Pi or any other one, and that will give the real drone all the acquired skill of the virtual drone from the simulation world in the real world.

PS: Whenever I use the word "all", please remember that in reality we live in a stochastic world, it can't always be 100%, with uncertainties and flaws the percentage decreases. 
For more clarity :

+1. The virtual simulation is made in Unity 3D.\
+2. The quadcopter drone model is made in Unity 3D too, following an open source course of drone simulations as well as a C# Language course.\
+3. The algorithm chosen for this matter is of a Deep Reinforcement Learning technique called PPO or Proximal Policy Optimization. Implemented in Unity 3D via ML-Agents.\
+4. Simulation-to-real-world transfer concerns itself with learning skills in simulation and then transferring them to the real world. It's a solid approach.

With all that being said, I just want to precise that this project will continue focusing on the software aspect of this whole idea for now, the hardware side of it will be treated once the software is finally finely tuned. So, for now, let's build the virtual autonomous drone !

tl;dr : The goal of this project is to achieve the conception of an autonomous drone that is capable of flying itself to a given location, evenly taking the shortest path and avoiding all collisions in its way with no human intervention.
