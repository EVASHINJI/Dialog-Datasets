# Personality Assignment Dataset

**类型：** 单轮、中文、开放领域

**来源：** 微博

**规模： ** 9, 697, 651 pairs

**下载链接：**

[http://coai.cs.tsinghua.edu.cn/file/ijcai_data.zip](http://coai.cs.tsinghua.edu.cn/file/ijcai_data.zip)



**构造方法：**

1. Weibo Dataset(WD) - 微博抓取数据，9, 697, 651 pairs 

2. Profile Binary Subset(PB) -  微博抓取数据中，通过表达式匹配profile的相关句子{姓名，性别，年龄，城市，体重，星座}，76, 930 pairs，13个人标注为某个设定下的正负例

3. Profile Related Subset - PB当中跟profile相关的正例，42, 193 pairs

4. Manual Dataset - 人工写的与profile相关的正负例句子

   

**公开数据的论文：**

Qian, Qiao, et al. "Assigning personality/identity to a chatting machine for coherent conversation generation." [Link](https://arxiv.org/pdf/1706.02861.pdf)

**使用数据的论文：**

