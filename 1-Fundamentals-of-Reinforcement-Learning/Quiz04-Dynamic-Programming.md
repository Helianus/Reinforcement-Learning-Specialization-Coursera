# Quiz04-Dynamic-Programming

## 1. The value of any state under an optimal policy is ___  the value of that state under a non-optimal policy. [Select all that apply]

![image-20210114165746040](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114165746040.png)

**Note**: A policy that is non optimal may still be optimal in some parts of the MDP. In these parts, it is possible that a non optimal policy could achieve the same values as an optimal policy.



## 2.1 If a policy is greedy with respect to the value function for the equiprobable random policy, then it is **guaranteed** to be an optimal policy.

![image-20210114165832693](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114165832693.png)



## 2.2 If a policy $\pi$ is greedy with respect to its own value function $v_{\pi}$, then it is an optimal policy.
![image-20210114170014079](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114170014079.png)



## 3. Let $v_{\pi}$ be the state-value function for the policy \pi*π*. Let $v_{\pi'}$ be the state-value function for the policy $\pi$'. Assume $v_\pi = v_\pi'$. Then this means that $\pi = \pi'$.

![image-20210114170201955](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114170201955.png)



## 4. What is the relationship between value iteration and policy iteration? [Select all that apply]

![image-20210114170229074](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114170229074.png)



## 5. The word synchronous means "at the same time". The word asynchronous means "not at the same time". A dynamic programming algorithm is: [Select all that apply]

![image-20210114170357463](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114170357463.png)



## 6.1 Policy iteration and value iteration, as described in chapter four, are synchronous.

![image-20210114170419089](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114170419089.png)



## 6.2 All Generalized Policy Iteration algorithms are synchronous.

![image-20210114170449787](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114170449787.png)



## 7. Which of the following is true?

![image-20210114170512898](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114170512898.png)



## 8. Why are dynamic programming algorithms considered planning methods? [Select all that apply]

![image-20210114170554182](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114170554182.png)



## 9.1 Consider the undiscounted, episodic MDP below. There are four actions possible in each state, A = {up, down, right, left}, which deterministically cause the corresponding state transitions, except that actions that would take the agent off the grid in fact leave the state unchanged. The right half of the figure shows the value of each state under the equiprobable random policy. If $\pi$ is the equiprobable random policy, what is $q$(7,down)?

![image-20210114170732328](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114170732328.png)

**Note**: $q(7, \text{down}) = -1 + v_{\pi}(11) = -1 + -14 = -15$.

## 9.2 Consider the undiscounted, episodic MDP below. There are four actions possible in each state, A = {up, down, right, left}, which deterministically cause the corresponding state transitions, except that actions that would take the agent off the grid in fact leave the state unchanged. The right half of the figure shows the value of each state under the equiprobable random policy. If $\pi$ is the equiprobable random policy, what is $q$(11,down)?

![image-20210114170936336](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114170936336.png)

**Note**: $q(11,\text{down})=-1 + T = -1 + 0= -1$.



## 10. Consider the undiscounted, episodic MDP below. There are four actions possible in each state, A = {up, down, right, left}, which deterministically cause the corresponding state transitions, except that actions that would take the agent off the grid in fact leave the state unchanged. The right half of the figure shows the value of each state under the equiprobable random policy. If $\pi$ is the equiprobable random policy, what is $v(15)$? Hint: Recall the Bellman equation $v(s) = \sum_a \pi(a | s) \sum_{s’, r} p(s’, r | s, a) [r + \gamma v(s’)]$.

![image-20210114171135472](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114171135472.png)

![image-20210114171144085](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20210114171144085.png)