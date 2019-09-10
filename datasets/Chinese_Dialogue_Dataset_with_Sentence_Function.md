# Chinese Dialogue Dataset with Sentence Function

**类型：** 单轮、中文、开放领域

**来源：** 微博

**规模：** 1,963,382 pairs

**下载链接：**

http://coai.cs.tsinghua.edu.cn/file/DialogwithSenFun.tar.gz



**构造方法：**

1. 1000万条微博抓取数据
2. 采样2000条进行人工标注，标注Sentence Function（Interrogative, Declarative, Imperative, and Exclamatory），train:valid:test=6:1:1 训练Sentence Function分类器
3. 用Sentence Function分类器对微博文本进行分类打上标签，每个类别采样约600万条



**其他标签：**

Sentence Function：Interrogative, Declarative, Imperative, and Exclamatory



**公开数据的论文：**

Ke, Pei, et al. "Generating informative responses with controlled sentence function."[Link](http://coai.cs.tsinghua.edu.cn/hml/media/files/acl_senfun.pdf)



**使用数据的论文：**

