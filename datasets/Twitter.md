# Twitter

**类型：** 单轮、英文、开放领域

**来源：** Twitter 2009年夏2个月数据

**规模：**

130万pairs

69%的post只有1个response，最多的有242个



**下载链接：**

http://www.cs.washington.edu/homes/aritter/twitter_chat/ (已失效)

后续衍化 http://research.microsoft.com/convo/

这里数据的关系整理的还不是非常清晰，就目前来看，许多用到Twitter数据集的论文都会回到这个[数据集](https://www.aclweb.org/anthology/N10-1020)或者这个数据集[衍化版本](https://arxiv.org/pdf/1506.06714.pdf)上。具体的关系后续进行补充。



**存在问题：**

1. 拼写问题。使用Jcluster word clustering算法对词进行聚类，发现同样的词有非常多的拼写形式。



**公开数据的论文：**

Ritter, Alan, Colin Cherry, and Bill Dolan. "Unsupervised modeling of twitter conversations." [Link](https://www.aclweb.org/anthology/N10-1020)



**相关论文：**

1. Ritter, Alan, Colin Cherry, and William B. Dolan. "Data-driven response generation in social media."
2. Sordoni, Alessandro, et al. "A neural network approach to context-sensitive generation of conversational responses."
3. 其他相关论文，Microsoft Data-Driven Conversation Dataset [Link](https://www.microsoft.com/en-us/research/project/data-driven-conversation/?from=http%3A%2F%2Fresearch.microsoft.com%2Fconvo%2F#!publications)



