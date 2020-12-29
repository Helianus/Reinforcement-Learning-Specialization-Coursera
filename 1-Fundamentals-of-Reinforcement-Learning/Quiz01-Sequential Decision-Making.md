# Quiz01-Sequential Decision-Making

## 1. What is the incremental rule (sample average) for action values?

![image-20201222120110344](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201222120110344.png)

## 2. Equation 2.5 (from the SB textbook, 2nd edition) is a key update rule we will use throughout the Specialization. We discussed this equation extensively in [video](https://www.coursera.org/learn/fundamentals-of-reinforcement-learning/lecture/XWqhe/estimating-action-values-incrementally). This exercise will give you a better hands-on feel for how it works. The blue line is the target that we might estimate with equation 2.5. The red line is our estimate plotted over time.

$q_{n+1}=q_n+\alpha_n[R_n -q_n]$

Given the estimate update in red, what do you think was the value of the step size parameter we used to update the estimate on each time step?

![img](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/E4RJl4cKEemA0BK4cRbOlg_acc93e119b1793005c3be9b36e9295c4_chart-_4_.png?expiry=1608768000000&hmac=BimcZsRzER_cbX6jpx09PCHzurp6h2sKEsWLP7PwqhY)

![image-20201222120309157](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201222120309157.png)



## 3. Equation 2.5 (from the SB textbook, 2nd edition) is a key update rule we will use throughout the Specialization. We discussed this equation extensively in [video](https://www.coursera.org/learn/fundamentals-of-reinforcement-learning/lecture/XWqhe/estimating-action-values-incrementally). This exercise will give you a better hands-on feel for how it works. The blue line is the target that we might estimate with equation 2.5. The red line is our estimate plotted over time.

$q_{n+1}=q_n+\alpha_n[R_n -q_n]$

Given the estimate update in red, what do you think was the value of the step size parameter we used to update the estimate on each time step?

![img](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/1YaT04cKEemVeg5DpI4LqA_1e09c6b42858c4b8e728a9db745a0ec7_chart-_5_.png?expiry=1608768000000&hmac=oDinBdyavBCPVq78aeSPBUHlKuTR7rxjAPNMUt3BEBI)

![image-20201222120404771](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201222120404771.png)



## 4. Equation 2.5 (from the SB textbook, 2nd edition) is a key update rule we will use throughout the Specialization. We discussed this equation extensively in [video](https://www.coursera.org/learn/fundamentals-of-reinforcement-learning/lecture/XWqhe/estimating-action-values-incrementally). This exercise will give you a better hands-on feel for how it works. The blue line is the target that we might estimate with equation 2.5. The red line is our estimate plotted over time.

$q_{n+1}=q_n+\alpha_n[R_n -q_n]$

Given the estimate update in red, what do you think was the value of the step size parameter we used to update the estimate on each time step?

![img](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/5oQYd4cKEemVeg5DpI4LqA_5023925429e9e1859eacaf528561f8d9_chart-_6_.png?expiry=1608768000000&hmac=Y0NoxN1DMlinGjLMBuOv0BNi6COfu_f9MCbdNV71g0o)

![image-20201222120436681](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201222120436681.png)



## 5. Equation 2.5 (from the SB textbook, 2nd edition) is a key update rule we will use throughout the Specialization. We discussed this equation extensively in [video](https://www.coursera.org/learn/fundamentals-of-reinforcement-learning/lecture/XWqhe/estimating-action-values-incrementally). This exercise will give you a better hands-on feel for how it works. The blue line is the target that we might estimate with equation 2.5. The red line is our estimate plotted over time.

$q_{n+1}=q_n+\alpha_n[R_n -q_n]$

Given the estimate update in red, what do you think was the value of the step size parameter we used to update the estimate on each time step?

![img](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/-CfvTIcKEemVeg5DpI4LqA_5d2a80708c491acae15e2f42604ef2b4_chart-_7_.png?expiry=1608768000000&hmac=UE5yK1rbLWwTtsCuc9AuC9r22pl5w68mvZVT8IQT6nI)

![image-20201222120508509](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201222120508509.png)



## 6. What is the exploration/exploitation tradeoff?

![image-20201222120538887](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201222120538887.png)



## 7. Why did epsilon of 0.1 perform better over 1000 steps than epsilon of 0.01?

![img](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/OdNsrHbGEemVOgruE3X9hg_1d72d77ad61d5d80678e869fa6f793d8_download.png?expiry=1608768000000&hmac=4TB92P4STEkc6Limbp50CYGtRuN7SWJYNTVzIhW6evc)

![image-20201222120607418](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201222120607418.png)



## 8. If exploration is so great why did epsilon of 0.0 (a greedy agent) perform better than epsilon of 0.4?

![img](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/8VaPyIcMEemNChIBV74tfA_9eaa84f77f36743c871b8cc26b5c2265_quiz-image.png?expiry=1608768000000&hmac=y-2f5gXtmPaP1xJQZtqMzjYgq5yfUxMXCYSj1HGxlaI)

![image-20201222120632551](C:\Users\Helia\AppData\Roaming\Typora\typora-user-images\image-20201222120632551.png)