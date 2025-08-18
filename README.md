# COMPSCI7209
Use Poisson Distribution to Predict football correct scores
1. Introduction
#Background/Context
Being the most popular sport, football is no longer purely a sport but also an economy. The value in the football business is enormous, with gambling on football contributing a large portion. In 2023 to 2024, the amount of football betting in Hong Kong reached 160 billion HKD(Hong Kong Jockey Club, n.d.) .
Football goals are relatively rare, discrete events, making the Poisson distribution a natural fit for modelling score outcomes(Paul Trevor,2024). In this report, I am going to use this statistical model to predict scores and apply different approaches to improve accuracy.
Motivation
In Football Gambling, there are lots of bets options,such as the result( Home win, draw, Away win), and number of goals, corner kicks , but the highest odds is the exact scoreline of the game, which indicates that the probability of getting the correct score is the lowest(Tochukwu Richard ,2025) . Since the minimum odds for exact scorelines are typically around 6.0, an accuracy of at least 17% is required to make a positive expected return in the long run(Aussportsbetting.com, n.d.). 
Proposed Solution
This project investigates whether refining the estimation of λ in the Poisson distribution and applying different data preprocessing ,such as number of Matches counted, excluding different extreme cases, can significantly improve prediction accuracy of football match scores over traditional average-based approaches.
Contributions
Developed and implemented a Poisson-based score prediction framework with three λ estimation methods and four preprocessing pipelines.
Designed a method to construct seasonal labels and filter out irrelevant or extreme match data.
Evaluated model performance across leagues and seasons, revealing insights into the effectiveness of regression-based and simple mean approaches in real-world football data.
