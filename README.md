# CS-370
Project Overview

In this project, I developed a Pirate Intelligent Agent capable of navigating a maze to locate hidden treasure using Deep Q-Learning, a reinforcement learning algorithm. The environment was modeled as a grid-based maze where the agent (pirate) learns optimal paths by receiving rewards and penalties for its actions.

I was provided with starter code for the environment setup, including the TreasureMaze and GameExperience classes, as well as partial code for initializing the neural network and visualization tools. The provided files defined the maze’s structure, reward system, and core gameplay logic but left the Q-training algorithm and agent decision-making components for me to implement.

The code I created focused on developing the deep reinforcement learning model that powers the pirate’s intelligence. Specifically, I implemented:

The Q-training loop (qtrain function) that trains the model using experience replay.

The ε-greedy policy to balance exploration and exploitation.

Integration of neural network predictions to approximate Q-values for each possible move.

Logic to monitor training performance and evaluate the agent’s success rate.

This combination allowed the pirate to progressively learn and improve its navigation decisions until it could consistently reach the treasure without human intervention.

Connecting Learning to the Field of Computer Science
What Do Computer Scientists Do and Why Does It Matter?

Computer scientists design, analyze, and implement systems that solve real-world problems through computation. Their work drives innovation across industries—powering advancements in artificial intelligence, cybersecurity, data analysis, and software development. By creating intelligent systems like the Pirate Agent, computer scientists contribute to automation, optimization, and decision-making processes that improve human efficiency and safety. Ultimately, their work matters because it enables society to use technology to make data-driven, ethical, and scalable solutions to complex challenges.

How Do I Approach a Problem as a Computer Scientist?

As a computer scientist, I approach problems analytically and iteratively. I begin by breaking down a problem into smaller components, researching existing algorithms or models, and determining which techniques best fit the scenario. In this project, I identified that reinforcement learning was the ideal framework because the pirate agent needed to learn from experience in an environment without a predefined path. From there, I designed a neural network architecture, implemented the learning algorithm, tested the model’s performance, and refined it based on outcomes. This structured, data-driven approach allows computer scientists to create efficient and adaptive solutions.

What Are My Ethical Responsibilities to the End User and the Organization?

Ethical responsibility in computer science involves ensuring that systems are safe, transparent, and fair. As a developer, I must consider how algorithms affect users and organizations, especially regarding privacy, bias, and accountability. For example, while the Pirate Agent operates in a simulated environment, similar reinforcement learning systems used in real-world applications—like autonomous vehicles or recommendation systems—must be designed to avoid harm and protect user data. Ethically, I am responsible for ensuring that my code performs reliably, that the results are interpretable, and that the system aligns with the organization’s goals without compromising user trust or safety.

Conclusion

This project demonstrated how reinforcement learning can transform a simple pathfinding problem into an opportunity for autonomous decision-making. Through coding the Pirate Intelligent Agent, I applied fundamental computer science principles—problem decomposition, algorithmic design, and ethical reasoning—to create an adaptive AI system. This experience reinforced how computer science blends technical skill with critical thinking to produce technology that both solves problems and respects the ethical boundaries of its users and stakeholders.
