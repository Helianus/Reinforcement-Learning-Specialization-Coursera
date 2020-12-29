# Quiz03-Value-Functions-and-Bellman-Equations

## 1. A function which maps ___ to ___ is a value function. [Select all that apply]

![image-20201229234129660](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201229234129660.png)



## 2. Consider the continuing Markov decision process shown below. The only decision to be made is in the top state, where two actions are available, left and right. The numbers show the rewards that are received deterministically after each action. There are exactly two deterministic policies, $\pi_{\text{left}}$ and $\pi_{\text{right}}$. Indicate the optimal  policies if $\gamma = 0$? If $\gamma = 0.9$? If $\gamma = 0.5$? [Select all that apply]

![img](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/-h-k6X2uEem3uwrt2iBKLA_108298e0c7f87e9372295d9320c097b2_right-or-left-_1_-1.png?expiry=1609372800000&hmac=Ihid_6ni1QkTrUlz0DGBFDdYXFuzdus7ls0U2yMjs18)

![image-20201229234324358](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201229234324358.png)

![image-20201229234338123](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201229234338123.png)



## 3. Every finite Markov decision process has  __. [Select all that apply]

![image-20201229234407322](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201229234407322.png)

![image-20201229234418197](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201229234418197.png)



## 4. The ___ of the reward for each state-action pair, the dynamics function $p$,  and the policy $\pi$is _____ to characterize the value function $v_{\pi}$.  (Remember that the value of a policy $\pi$ at state $s$ is 

$$v_{\pi}(s) = \sum_a \pi(a | s) \sum_{s',r} p(s', r | s, a) [ r + \gamma v_{\pi}(s')].)$$

![image-20201229235244165](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201229235244165.png)

## 5. The Bellman equation for a given a policy \pi*π*: [Select all that apply]

![image-20201229235310194](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201229235310194.png)

## 6. An optimal policy:

![image-20201229235326749](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201229235326749.png)

## 7. The Bellman optimality equation for $v_{\ast}$: [Select all that apply]

![image-20201229235401359](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201229235401359.png)



## 8. Give an equation for $v_{\pi}$ in terms of $q_{\pi}$and $\pi$.

![image-20201229235452531](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201229235452531.png)

## 9. Give an equation for $q_{\pi}$ in terms of $v_{\pi}$ and the four-argument $p$.

![image-20201230000019801](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201230000019801.png)



## 10. Let $r(s,a)$ be the expected reward for taking action a*a* in state $s$, as defined in equation 3.5 of the textbook. Which of the following are valid ways to re-express the Bellman equations, using this expected reward function? [Select all that apply]

![image-20201230000118036](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201230000118036.png)

## 11. Consider an episodic MDP with one state and two actions (left and right). The left action has stochastic reward 11 with probability $p$ and 3 with probability $1-p$. The right action has stochastic reward 0 with probability $q$ and 10 with probability $1-q$. What relationship between $p$ and $q$ makes the actions equally optimal?

$$
\begin{align}
p+3-3p &= 10-10q \\
-2p+3 &= 10-10q \\
-2p-7 &= -10q \\
7+2p &= 10q \\
\end{align}
$$

![image-20201230000129235](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201230000129235.png)

