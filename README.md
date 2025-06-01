
## Offline Evaluation Code for Master's Thesis

This repository contains the source code for the offline evaluation conducted as part of my master's thesis. Certain aspects have been censored to protect business-sensitive information.


### Thesis title: 
Enhancing Media Streaming Platforms with Contextual Recommendations
#### Abstract:
Recommender systems have become tremendously important in online platforms such as e-commerce and media streaming. Such systems seek to provide personalised recommendations to the end users, thereby mitigating information overload and improving user satisfaction. Certain recommender systems, however, are not context-aware, meaning they do not consider the information surrounding the users’ environment (e.g., time of day, weather, geolocation). The lack of context-awareness can be a significant oversight since the context can affect user behaviour to a great degree, which traditional recommender systems cannot take into account, thereby limiting their performance. This could lead to irrelevant or insufficient recommendations for the end users. Contextual post-filtering is a technique for context integration that contextualises recommendations after they have been made by the underlying recommender system. This blends personalisation with contextual relevance to deliver recommendations that align with user preferences and the surrounding context.

This thesis proposes a novel post-filtering approach that extends the collaborative
filtering algorithm Alternating Least Squares (ALS) to incorporate context following
time of day (i.e, morning, afternoon, evening, night). The proposed approach was tested
in both offline and online environments to evaluate its performance under controlled conditions and real-world scenarios. The offline evaluation was conducted by using historical viewing data from TV 2 Play, while the online evaluation was conducted in the form of an A/B test in its production environment.

During the online evaluation, the proposed post-filtering algorithm demonstrated gains in user engagement while recommending a more diverse set of items. By blending personalised recommendations with contextual relevance, contextual post-filtering increased user engagement without compromising on relevance. This contributed to more diverse, fair and novel recommendations, which resulted in increased user engagement.

---

Copyright © 2025 Thorstein Fougner