# Douban Conversation Corpus

**类型：**多轮、中文、开放领域

**来源：**豆瓣

**规模：**

session-response pairs 1,000,000 pairs

平均6.69轮每session



**下载链接：**

https://github.com/MarkWuNLP/MultiTurnResponseSelection



**构造方法：**

1. 豆瓣小组中轮数大于2轮的110万

2. 50万做训练集，从110万中其他句子中sample负例

   

**公开数据的论文：**

Wu, Yu, et al. "Sequential matching network: A new architecture for multi-turn response selection in retrieval-based chatbots." [Link](https://pdfs.semanticscholar.org/a6ee/c00f10346ce27d4f69f9e38f5665fffe8056.pdf)



**使用数据的论文：**

1. Zhou, Xiangyang, et al. "Multi-turn response selection for chatbots with deep attention matching network."
2. Zhang, Zhuosheng, et al. "Modeling multi-turn conversation with deep utterance aggregation."
3. Wu, Yu, et al. "Learning matching models with weak supervision for response selection in retrieval-based chatbots."