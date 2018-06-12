# Reinforcement Learning for Dino_run


![image](https://github.com/baker12355/Dino_run/blob/master/dino.gif)


# 強化學習
> 訓練方式:
>> 1.觀察
>> 2.選擇行為


![image](https://github.com/baker12355/Dino_run/blob/master/RL_illustration_1.PNG)


![image](https://github.com/baker12355/Dino_run/blob/master/RL_illustration_2.PNG)





https://www.youtube.com/watch?v=W8XF3ME8G2I&index=34&list=PLJV_el3uVTsPy9oCRY30oBPNLCo89yu49&t=0s


1. What kind of RL algorithms did you use? value-based, policy-based, model-based? why? (10%)
2. This algorithms is off-policy or on-policy? why? (10%)
3. How does your algorithm solve the correlation problem in the same MDP? (10%)

回答1: value-based algorithm, DQN使用神經網路作為Q-table的依據，在這邊我們輸出只有兩個(不跳與跳)，而神經網路輸出大值為即將採取的動作，故只比較Q-value大小，為values-based。
回答2:這是一個off-policy的algorithms，因為在選擇動作時加入了一個隨機動作的可能性，已達到更好的探索空間。
回答3:
