# Quiz02-MDPs

## 1. The learner and decision maker is the _______.

![image-20201225222156385](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225222156385.png)

## 2. At each time step the agent takes an _______.

![image-20201225222224730](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225222224730.png)

## 3. Imagine the agent is learning in an episodic problem. Which of the following is true?

![image-20201225222249818](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225222249818.png)

## 4. If the reward is always +1 what is the sum of the discounted infinite return when $\gamma < 1$

![image-20201225222331621](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225222331621.png)



## 5. What is the difference between a small gamma (discount factor) and a large gamma?
![image-20201225222405832](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225222405832.png)



## 6.1 Suppose $\gamma = 0.8$ and the reward sequence is $R_1 = 5$ followed by an infinite sequence of $10s$. What is $G_0$?
![image-20201225222522556](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225222522556.png)

## 6.2 Suppose $\gamma=0.8$ and we observe the following sequence of rewards: $R_1 = -3$*, $R_2 = 5$*, $R_3=2$, $R_4 = 7$, and $R_5 = 1$*, with $T=5$*. What is $G_0$? Hint: Work Backwards and recall that $G_t = R_{t+1} + \gamma G_{t+1}$.

$$
\begin{align}
G_5 &= 0 \\
G_4 &= 1 + 0.8\times0 = 1 \\
G_3 &= 7 + 0.8\times1 = 7.8 \\
G_2 &= 2 + 0.8\times7.8 = 8.24 \\
G_1 &= 5 + 0.8\times8.24 = 11.592 \\
G_0 &= -3 + 0.8\times11.592 = 6.2736 \\
\end{align}
$$



![image-20201225222816377](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225222816377.png)

## 7. What does MDP stand for?

![image-20201225222540035](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225222540035.png)



## 8. Suppose reinforcement learning is being applied to determine moment-by-moment temperatures and stirring rates for a bioreactor (a large vat of nutrients and bacteria used to produce useful chemicals). The actions in such an application might be target temperatures and target stirring rates that are passed to lower-level control systems that, in turn, directly activate heating elements and motors to attain the targets. The states are likely to be thermocouple and other sensory readings, perhaps filtered and delayed, plus symbolic inputs representing the ingredients in the vat and the target chemical. The rewards might be moment-by-moment measures of the rate at which the useful chemical is produced by the bioreactor. 

Notice that here each state is a list, or vector, of sensor readings and symbolic inputs, and each action is a vector consisting of a target temperature and a stirring rate. 

Is this a valid MDP?

![image-20201225222608032](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225222608032.png)



## 9.

**Case 1**: Imagine that you are a vision system. When you are first turned on for the day, an image floods into your camera. You can see lots of things, but not all things. You can't see objects that are occluded, and of course you can't see objects that are behind you. After seeing that first scene, do you have access to the Markov state of the environment? 

**Case 2**: Imagine that the vision system never worked properly: it always returned the same static imagine, forever. Would you have access to the Markov state then? (Hint: Reason about $P(S_{t+1} | S_t, ..., S_0)$, where $S_t = AllWhitePixels)$

![image-20201225223351926](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225223351926.png)



## 10. What is the reward hypothesis?

![image-20201225223413727](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225223413727.png)



## 11. Imagine, an agent is in a maze-like gridworld. You would like the agent to find the goal, as quickly as possible. You give the agent a reward of +1 when it reaches the goal and the discount rate is 1.0, because this is an episodic task. When you run the agent its finds the goal, but does not seem to care how long it takes to complete each episode. How could you fix this? (Select all that apply)
![image-20201225223452788](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225223452788.png)



## 12. When may you want to formulate a problem as episodic?

![image-20201225223514754](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201225223514754.png)



