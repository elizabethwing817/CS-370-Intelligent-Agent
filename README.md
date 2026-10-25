# CS-370 Intelligent Agent

**Course:** CS-370 – Current/Emerging Trends in Computer Science  
**University:** Southern New Hampshire University

---

## Project Overview

This project focused on developing an intelligent pirate agent that could navigate a maze and locate treasure using deep Q-learning. Instead of programming a specific route for the pirate to follow, the goal was to train an agent that could learn from its experiences and make decisions based on rewards.

The project demonstrates how reinforcement learning and neural networks can be used to solve pathfinding problems.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Jupyter Notebook
- Deep Q-Learning
- Neural Networks

## Project Development

SNHU provided the starter Jupyter Notebook along with the TreasureMaze and GameExperience Python classes. These files established the maze environment and provided the structure for storing experiences during training.

My primary responsibility was completing the deep Q-learning training algorithm. I implemented an epsilon-greedy strategy to balance exploration and exploitation, used experience replay to train the model on previous interactions, and incorporated a target network to improve training stability.

The neural network predicted Q-values for four possible movements: left, up, right, and down.

## Project Results

The agent reached a 100% recent win rate and met its stopping conditions after 308 training epochs, taking approximately 398.8 seconds. I also tested the trained model against the valid starting positions in the maze, and the completion check returned True.

These results demonstrated that the agent could learn successful navigation strategies without having every route programmed manually.

## Reflection

### What do computer scientists do, and why does it matter?

Computer scientists use technology, programming, and problem-solving skills to develop solutions to different challenges. Their work matters because software affects so many parts of everyday life, from the applications people use to the systems businesses depend on. This project showed me how computer science can go beyond writing instructions and allow a system to learn from experience.

### How do I approach a problem as a computer scientist?

I approach problems by breaking them into smaller pieces, understanding what needs to be accomplished, and testing possible solutions. During this project, I had to consider how the pirate would learn, how to balance exploration and exploitation, and how to measure whether the training was successful. I also learned that getting a good result is not enough by itself. Testing the model from different starting positions helped me determine whether it could consistently solve the problem.

### What are my ethical responsibilities to the end user and the organization?

As a computer scientist, I have a responsibility to develop software that is reliable, secure, and fair to the people who use it. This includes protecting user information, considering potential risks, and testing systems before they are released. Artificial intelligence introduces additional responsibilities because its decisions depend on training data and the way it is designed. Developers need to understand the limitations of their systems and avoid assuming that successful results in one environment guarantee success in every situation.

## Conclusion

This project helped me better understand reinforcement learning and how neural networks can be used to make decisions. It also reinforced the importance of testing, evaluating results, and improving a solution rather than assuming the first approach will work. These are skills I can continue applying throughout my computer science career.
