# machine_learning_trading_bot_strategy
___
### SVC model comparing baseline model using 3 months of training data and then using 6 months of training data. SMA Fast = 4. SMA Slow = 100
##### *First image is using 3 months of data and the SMA Fast = 4 SMA Slow = 100. The second graph is using 6 months of training data*
<img width="482" alt="Screen Shot 2022-04-10 at 5 40 08 PM" src="https://user-images.githubusercontent.com/95598560/162647477-5bb4b911-2ece-478c-a6bd-731c82a12367.png">
<img width="458" alt="Screen Shot 2022-04-10 at 5 42 54 PM" src="https://user-images.githubusercontent.com/95598560/162647728-db88400a-26fd-4201-870c-31d7a6a18588.png">

## Analysis: What impact resulted from increasing or decreasing the training window?

#### Answer: After switching from 3 months of training data to 6 months of training data, it seems like using a shorter time frame (3 months) provided better strategy returns, especially earlier 
___


### Model Comparing the baseline model with a switch in the SMA Fast and SMA Slow length. Originally the SMA Fast = 4 and SMA Slow = 100. Switched the SMA Fast to equal 12 and SMA Slow to equal 150.
<img width="482" alt="Screen Shot 2022-04-10 at 5 40 08 PM" src="https://user-images.githubusercontent.com/95598560/162647477-5bb4b911-2ece-478c-a6bd-731c82a12367.png">
<img width="566" alt="Screen Shot 2022-04-10 at 6 00 53 PM" src="https://user-images.githubusercontent.com/95598560/162648727-ff82d482-dc25-405f-bd94-8e834329343a.png">

## Analysis:  What impact resulted from increasing or decreasing either or both of the SMA windows?

#### Answer: When switching the SMA windows to 12 and 150 instead of 4 adn 100, we see that Baseline model still seems to predict better strategy returns from the end of 2018 until the end.

##### Overall conclusion: I would still need to test different SMA Windows as well as time frames to find the best strategy. None of the strategies are perfect and it will be difficult to find a perfect strategy anyways. 
