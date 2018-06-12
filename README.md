# Reinforcement Learning for Dino_run


![image](https://github.com/baker12355/Dino_run/blob/master/dino.gif)


# 強化學習
##  環境描述

> 1.觀察 2.選擇行為 3.行動 4.獲得reward 
![image](https://github.com/baker12355/Dino_run/blob/master/RL_illustration_1.PNG)

以示意圖而言Agent觀察環境，並且行動打翻水杯，獲得一個負向的reward。而這次的動作會影響環境，下一個State會從打翻水杯後開始，若此時選取動作:清理打翻的水杯，則會獲得一個正向的reward。
![image](https://github.com/baker12355/Dino_run/blob/master/RL_illustration_2.PNG)


## 訓練方式

> 首先讓Agent在空間中探索，並且記錄每一次的探索經驗(S,A,R,St+1,Terminal)，狀態(time=t)、動作、報酬、動作後狀態(time=t+1)、是否終止。反覆重複N次作> 為訓練資料，其中每次的動作是由Q-Table來決定的，我們訓練的目的即為最佳化Q-Table使得我們的Agent可以得到最多的reward。
![image](https://github.com/baker12355/Dino_run/blob/master/q-table.png)



1. What kind of RL algorithms did you use? value-based, policy-based, model-based? why? (10%)
2. This algorithms is off-policy or on-policy? why? (10%)
3. How does your algorithm solve the correlation problem in the same MDP? (10%)

回答1: value-based algorithm, DQN使用神經網路作為Q-table的依據，在這邊我們輸出只有兩個(不跳與跳)，而神經網路輸出大值為即將採取的動作，故只比較Q-value大小，為values-based。
回答2:這是一個off-policy的algorithms，因為在選擇動作時加入了一個隨機動作的可能性，已達到更好的探索空間。
回答3:






https://www.youtube.com/watch?v=W8XF3ME8G2I&index=34&list=PLJV_el3uVTsPy9oCRY30oBPNLCo89yu49&t=0s
