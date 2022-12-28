# Machine Learning Trading Algorithm Bot
## Tune the Baseline Trading Algorithm
### Step 1: Tune the training algorithm by adjusting the size of the training dataset. To do so, slice your data into different periods. Rerun the notebook with the updated parameters
#### Ending period for the training data with an offset of 3 months_

![alt=""](Images/eval_step3_backtest.JPG)

![alt=""](Images/plotResult_actRet_vs_stratRet.png)

#### Ending period for the training data with an offset of 6 months_
![alt=""](Images/6mos-classificationrpt-svc-model.JPG)

![alt=""](Images/plotResult_actRet_vs_stratRet-6mos.png)

#### What impact resulted from increasing or decreasing the training window?
The increase for training data with an offset of 6 months from 3 months gave us 56% accuracy using the SVC model compared to 52% accuracy of using logistic regression. Both have equal percentages on the precision for both buy & sell block however, the percentage on recall has widely increased to 98% on SVC model from the 66% for the logistic regression.

### Step 2: Tune the trading algorithm by adjusting the SMA input features
#### What impact resulted from increasing or decreasing either or both of the SMA windows?

### Step 3: Choose the set of parameters that best improved the trading algorithm returns
#### Save a PNG image of the cumulative product of the actual returns vs. the strategy returns

