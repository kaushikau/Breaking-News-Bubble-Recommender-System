# Breaking the News Content Bubble: A Hybrid Recommendation System Approach

*Kaushika Uppu, Miranda Billawala*

***Abstract —*** News recommender systems often prioritize maximizing user engagement, leading to a push on content that users are highly likely to agree with and reflect their perspectives or points of view. However, that tends to lead to a news content bubble where users are not exposed to conflicting perspectives. In this project, we aimed to alleviate that issue by first predicting the probability of a user clicking on an article and then using that to recommend atypical articles that would still catch their interest. We found that XGBoost performed better than NCF for predicting probability, with an AUC of 0.644 and a recall of 0.414. For the recommendations, due to the models not predicting click probability well, accuracy was very low.

***Keywords —*** *recommendation system, news, content bubble, bias*
