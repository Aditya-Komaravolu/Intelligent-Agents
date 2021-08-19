# Intelligent-Agents

An **agent** is anything that can be viewed as perceiving its environment through **sensors** and acting upon that environment through **effectors**.

In ***Artificial Intelligence***, an **intelligent agent** is anything which perceives its environment, takes actions autonomously in order to achieve goals, and may improve its performance with learning or may use knowledge.

## Problem Statement: (VACUUM CLEANER)
You are given a imaginary 5x5 room with integer dirt in each block (See images below). Follow the rules given below and develop the agents!

![image](https://user-images.githubusercontent.com/64011471/130115347-f6ddac10-e19c-4f4b-818e-28ce93d8274d.png)

![image](https://user-images.githubusercontent.com/64011471/130115372-bd08c184-59ab-48f6-9371-159ea77edfe5.png)

![image](https://user-images.githubusercontent.com/64011471/130115407-9610902f-7d0e-41ce-89be-16bbd7a27f13.png)

![image](https://user-images.githubusercontent.com/64011471/130115427-ecf05505-9758-45f3-b2d4-56e229537fa6.png)

![image](https://user-images.githubusercontent.com/64011471/130115449-c6ce6c58-831a-4fc6-a2d4-c0976eafbd65.png)

# *Video About Problem statement and explanation of code ->[Click Here](https://drive.google.com/file/d/12vz-MzxWKL9P-ErJg4dDb61lDQU69z25/view?usp=sharing)*


# (NOTE: All the graphical representations are completely based on the use-case of this repo.)
#### Agents can be grouped into five classes based on their degree of perceived intelligence and capability:

## Simple Reflex Agent:
* The ***Simple reflex agents*** are the simplest agents. These agents take decisions on the basis of the current percepts and ignore the rest of the percept history.
* These agents only succeed in the fully observable environment.
* The Simple reflex agent does not consider any part of percepts history during their decision and action process.

![image](https://user-images.githubusercontent.com/64011471/130102867-3cdf88cf-4458-4345-86af-5152822076c2.png)
## Model Based Reflex Agent:
The ***Model-based reflex agent*** can work in a partially observable environment, and track the situation.
A model-based agent has two important factors:
* Model: It is knowledge about "how things happen in the world," so it is called a Model-based agent.
* Internal State: It is a representation of the current state based on percept history.

These agents have the model, "which is knowledge of the world" and based on the model they perform actions.

![image](https://user-images.githubusercontent.com/64011471/130103513-2d118b4b-9504-4602-94d2-5b5902e1d1f1.png)
## Goal Based Agent:
* The knowledge of the current state environment is not always sufficient to decide for an agent to what to do.
* The agent needs to know its goal which describes desirable situations.
* ***Goal-based agents*** expand the capabilities of the ***model-based reflex agent*** by having the "goal" information.
* They choose an action, so that they can achieve the goal.
* These agents may have to consider a long sequence of possible actions before deciding whether the goal is achieved or not. Such considerations of different scenario are called searching and planning, which makes an agent proactive.

![image](https://user-images.githubusercontent.com/64011471/130103649-e49355bc-6573-4e82-8b6e-d3f46fd1c903.png)
## Utility Based Agent:
* These agents are similar to the goal-based agent but provide an extra component of utility measurement which makes them different by providing a measure of success at a given state.
* ***Utility-based agent*** act based not only goals but also the best way to achieve the goal.
* The Utility-based agent is useful when there are multiple possible alternatives, and an agent has to choose in order to perform the best action.
* The utility function maps each state to a real number to check how efficiently each action achieves the goals.

![image](https://user-images.githubusercontent.com/64011471/130103673-c2be824b-74c3-4b22-b85a-f4218a5868f6.png)
## Learning Based Agent:
* A learning agent in AI is the type of agent which can learn from its past experiences, or it has learning capabilities.
* It starts to act with basic knowledge and then able to act and adapt automatically through learning.
* A ***learning agent*** has mainly four conceptual components, which are:
   *  Learning element: It is responsible for making improvements by learning from environment and remembering about it.
   *  Goal element: It is reponsible for reaching the required goal state.
   * Performance element: It is responsible for iteratively finding out all possible ways to reach the goal state and choose the best method.

Hence, learning agents are able to learn, analyze performance, and look for new ways to improve the performance.

![image](https://user-images.githubusercontent.com/64011471/130103703-a5d7b3b6-e75e-4f00-b58a-9e797e4f0f52.png)

