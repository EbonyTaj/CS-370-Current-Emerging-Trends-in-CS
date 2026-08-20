# CS 370: Current/Emerging Trends in Computer Science

## Pirate Intelligent Agent

In this project, I worked with an intelligent pirate agent that had to learn how to move through a maze and find the treasure. Instead of programming the exact path the pirate should take, I used reinforcement learning to allow the agent to learn from its own experience.

A simple way I think about reinforcement learning now is learning through trial and error. The pirate makes a move, gets feedback from the environment, and uses that information when deciding what to do next. After enough practice, it starts making better decisions and becomes more likely to reach the treasure.

## What code were you given, and what code did you create yourself?

I was given starter code that provided the basic pieces of the project, including the maze environment and supporting classes. This meant I did not have to build the entire game from scratch. Instead, I could focus on the part that actually trained the pirate.

I completed the code needed to train the agent using Deep Q-Learning. The agent had to choose an action, see what happened, receive a reward or penalty, and remember that experience. I also used epsilon to balance exploration and exploitation. Early in training, the pirate explores more because it does not know which moves are best. As it learns, epsilon decreases and the pirate relies more on what it has already learned. Eventually, the agent was able to successfully navigate the maze and reach the treasure.

## What do computer scientists do, and why does it matter?

I think computer scientists are problem solvers. The code is important, but the bigger job is understanding a problem and figuring out how technology can help solve it. That might mean developing software, working with data, building an AI model, or improving a system that already exists.

This project helped me see why that matters with AI. Getting a program to run does not automatically mean it is doing the right thing. With reinforcement learning, the agent learns based on the rewards we give it. If I reward the wrong behavior, the agent can become very good at doing something I never intended. That makes the way we design and test these systems just as important as the code itself.

## How do I approach a problem as a computer scientist?

I have learned to start by understanding the problem and then break it into smaller pieces. With the pirate project, the big problem was simple: get the pirate to the treasure. Actually solving it required me to think about smaller questions. Where is the pirate now? What moves can it make? What happens after each move? What should count as a good or bad decision? How does it remember what happened before?

Breaking the problem down this way made it easier to understand what the code was doing and troubleshoot when something did not work as expected. I also learned that I should not expect the first solution to be perfect. Testing, looking at the results, making changes, and trying again are all part of solving the problem.

## What are my ethical responsibilities to the end user and the organization?

My responsibility does not stop once the program works. I also have to think about the people who will use the technology and the organization responsible for it. That includes protecting people's information, considering security and privacy, testing for unintended results, and being clear about what a system can and cannot do.

One of the biggest things I learned in this course is that an AI system learns from what we give it. The data, rewards, and feedback all influence the behavior it develops. That means developers have a responsibility to think about what the system is actually learning instead of assuming that because the technology works, the outcome will automatically be fair or useful.

## What I Learned

Before this course, I understood the general idea that AI could "learn," but I did not fully understand what that meant. Working with Deep Q-Learning made it much clearer.

The pirate was not thinking about the maze the way a person would. It was trying actions, seeing the result, and using those experiences to estimate which actions were more likely to lead to a better outcome. Experience replay allowed it to learn from previous experiences instead of only the most recent move, while the neural network helped it estimate the value of different actions.

Seeing all of those pieces work together helped reinforcement learning finally make sense to me. The biggest takeaway I have from this project is that teaching an intelligent agent is not just about giving it answers. It is about creating an environment where it can learn from experience and making sure the feedback we give it encourages the behavior we actually want.
