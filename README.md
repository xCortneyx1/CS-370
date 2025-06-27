# CS-370

**Overview**
This project demonstrates my ability to design and implement an intelligent agent using reinforcement learning and neural networks. Specifically, I developed a pirate agent capable of learning how to navigate a maze to reach a treasure before the player. This agent was trained using deep Q-learning in a simulated game environment.

**I was provided with starter code that included:**
  * A TreasureMaze.py class that defined the environment, including the maze and rules.
  * A GameExperience.py class that handled experience replay memory for training the agent.

**The code I created myself includes:**
  * A fully implemented DQN (Deep Q-Network) training loop inside a Jupyter Notebook.
  * Code for initializing the neural network architecture using TensorFlow/Keras.
  * The logic for selecting actions via an epsilon-greedy strategy.
  * The loop that handles training the agent using mini-batches from the replay memory.
  * Plotting tools to visualize the learning progress of the agent over episodes.

This notebook reflects my ability to integrate several concepts covered in this course into a working AI solution.

**Reflection**

**What do computer scientists do and why does it matter?**
Computer scientists develop software and intelligent systems that solve real-world problems, enhance automation, and improve human lives. Whether through designing algorithms, optimizing performance, or ensuring ethical AI use, their work powers nearly every modern industry—from healthcare to gaming. This project mirrors that purpose by simulating intelligent decision-making in a dynamic environment.

**How do I approach a problem as a computer scientist?**
I approach problems by breaking them into smaller, manageable components. In this project, I first understood the rules of the environment, then analyzed the learning algorithm needed, and finally implemented the components step-by-step. I tested each part (like the memory buffer and the Q-network) individually before integrating everything into a training loop. This structured, iterative approach is essential in computer science.

**What are my ethical responsibilities to the end user and the organization?**
As a developer of intelligent systems, I hold a responsibility to ensure that the systems I build are safe, fair, and transparent. In the case of reinforcement learning agents, especially those that make decisions autonomously, it’s important to monitor for unintended behaviors. As AI expands into healthcare, finance, and education, ensuring bias-free, explainable, and accountable systems is a moral and professional obligation.

