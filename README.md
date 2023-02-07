## Coursework from Northwestern's MS Data Science program
## MSDS 451 Financial Machine Learning

This course covered methods to improve statistical robustness in low signal to noise environments, explainable machine learning, and methods to avoid common pitfalls while using algorithms to develop and execute trading strategies. Primary material authored by Dr. Marcos Lopez De Prado and course content created by Dr. Ernest (Ernie) Chan.
- Fractional differentiation - acheiving stationarity without removing all memory from dataset
- Robust feature engineering using heirarchical MDA and MDI (pseudo-randomness does not allow convergence to true feature importances)
- Explainable ML - SHAP, LIME, etc. 
- Ergodic Theory
- Combinatorial cross validation (cross validation respecting non-ergodic properties)
- Backtesting strategies, pitfalls, and how to avoid them


| Primary Text | Secondary Text | Secondary Text|
| :-----------: | :-----------: | :---------: |
| ![AFML Cover](https://user-images.githubusercontent.com/87036676/217150942-59ffa1f2-92f3-4f96-8fe2-158b1a522288.jpg) | ![Machine Trading](https://user-images.githubusercontent.com/87036676/217219544-d941d16f-0bd2-4abf-85c4-e5f29a3d82de.jpg)|![ML for Asset Managers](https://user-images.githubusercontent.com/87036676/217220363-b7611d34-22d2-4eda-8973-9720d96bc1db.jpg)|
|![image source](https://www.wiley.com/en-us/Advances+in+Financial+Machine+Learning-p-9781119482086)|![image source](https://www.wiley.com/en-us/Machine+Trading:+Deploying+Computer+Algorithms+to+Conquer+the+Markets-p-9781119219606)|![image source](https://www.cambridge.org/core/elements/abs/machine-learning-for-asset-managers/6D9211305EA2E425D33A9F38D0AE3545)|


## Excerpts from the forward in Advances in Financial Machine Learning:
To my knowledge, this is the first book to provide a complete and systematic treatment of ML methods specific for finance: starting with a chapter dedicated to financial data structures, another chapter for labeling of financial series, another for sample weighting, time series differentiation, . . . all the way to a full part devoted to the proper backtesting of investment strategies. To be sure, there are a handful of prior publications (mostly journal articles) that have applied standard ML to financial series, but that is not what this book offers. My goal has been to address the unique nuisances that make financial ML modeling particularly challenging. Like any new subject, it is fast evolving, and the book will be updated as major advances take place. Please contact me at mldp@quantresearch.org if there is any particular topic you would like to see treated in future editions. I will gladly add those chapters, while acknowledging the names of those readers who suggested them.

Books about investments largely fall in one of two categories. On one hand we find books written by authors who have not practiced what they teach. They contain extremely elegant mathematics that describes a world that does not exist. Just because a theorem is true in a logical sense does not mean it is true in a physical sense. On the other hand we find books written by authors who offer explanations absent of any rigorous academic theory. They misuse mathematical tools to describe actual observations. Their models are overfit and fail when implemented. Academic investigation and publication are divorced from practical application to financial markets, and many applications in the trading/investment world are not grounded in proper science.

A second motivation is inspired by the desire that finance serves a purpose. Over the years some of my articles, published in academic journals and newspapers, have expressed my displeasure with the current role that finance plays in our society. Investors are lured to gamble their wealth on wild hunches originated by charlatans and encouraged by mass media. One day in the near future, ML will dominate finance, science will curtail guessing, and investing will not mean gambling. I would like the reader to play a part in that revolution.

A third motivation is that many investors fail to grasp the complexity of ML applications to investments. This seems to be particularly true for discretionary firms moving into the “quantamental” space. I am afraid their high expectations will not be met, not because ML failed, but because they used ML incorrectly. Over the coming years, many firms will invest with off-the-shelf ML algorithms, directly imported from academia or Silicon Valley, and my forecast is that they will lose money (to better ML solutions). Beating the wisdom of the crowds is harder than recognizing faces or driving cars. With this book my hope is that you will learn how to solve some of the challenges that make finance a particularly difficult playground for ML, like backtest overfitting. Financial ML is a subject in its own right, related to but separate from standard ML, and this book unravels it for you.
