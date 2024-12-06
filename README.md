# Explainable-emotion-analysis
This is core code for article [An explanation framework and method for AI-based text emotion analysis and visualisation](https://www.sciencedirect.com/science/article/pii/S0167923623001963)



## Introduction
It consists of three main components in the article:

- Emotion Cause Extraction
- Emotion Trigger Visualization
- Comparison with SHAP and LIME

## Emotion Cause Extraction
dataset adapted from [Emotion-Cause Pair Extraction: A New Task to Emotion Analysis in Texts](https://aclanthology.org/P19-1096) (Xia & Ding, ACL 2019)

## Emotion Trigger Visualisation

download emotion datasets before running 'emotion trigger words visualisation.ipynb'

- Bing.csv: [Bing, NRC, Afinn Lexicons from Kaggle] (https://www.kaggle.com/datasets/andradaolteanu/bing-nrc-afinn-lexicons)
- dict.xlsx: adapted from [Mining and summarizing customer reviews] (https://dl.acm.org/doi/abs/10.1145/1014052.1014073)
- senticnet.xlsx: [Senticnet](https://sentic.net/)

## Comparison
- SHAP: based on [Shapley Additive Explanation](https://www.sciencedirect.com/topics/computer-science/shapley-additive-explanation)
- LIME: based on [Local Interpretable Model-agnostic Explanation](https://arxiv.org/abs/1606.05386)
