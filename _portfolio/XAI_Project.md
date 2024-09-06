---
title: "XAI Project"
collection: portfolio
---

This project was performed as a part of the Explainable AI course. In this project, our group explored the link between hard drugs consumption and cannabis consumption based on the [Drug consumption dataset](https://arxiv.org/abs/1506.06297). In order to do this, drugs were separated based on the harm that they cause. LSD and Mushrooms were grouped as psychedelic drugs. Rest of the drugs were grouped as hard drugs. After EDA, features with biases were dropped. A Random Forest classifier was trained on the dataset and the parameters optimized with grid search. We used shapely values particularly TreeSHAP and Forest Guided Clustering(FGC) to explain the results. The validation of the XAI methods was done using feature, rank and sign agreement for TreeSHAP and clustering for FGC. [Github](https://github.com/AlbertNegura/XAI-UM-Project) 
