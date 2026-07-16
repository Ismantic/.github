# 是语实验室

- **低成本实践**
- **底层实现**

## 项目

是语百科 
- [IsEntity](https://github.com/Ismantic/IsEntity) 是语人物志，强类型Scheme的Entity库。（数据来自维基数据/维基百科）

  
是语输入法
- [Sime](https://github.com/Ismantic/Sime) 支持简繁/中英，以统计语言模型为核心的拼音输入法引擎。
- [IsCut](https://github.com/Ismantic/IsCut) 支持输入法项目用的EM中文分词算法，需要提前准备好词表与语料。
- [Handwritten](https://github.com/Ismantic/Handwritten) 补充手写汉字识别输入而训练的MobileNet-v2模型。


小模型
- [PieceTokenizer](https://github.com/Ismantic/PieceTokenizer) 相比SentencePiece，增加了更多的中文支持。
- [BERTc](https://github.com/Ismantic/BERTc) 模型结构有改进，泛化性更好，做了CWS/NER/POS与纠错的下游任务。
- [Wapic](https://github.com/Ismantic/Wapic) 蒸馏泛化性更好的BERT模型，得到速度更快的CRF模型。
- [Summer](https://github.com/Ismantic/Summer) 用ReTok方法给底座模型(Qwen3)换Tokenizer，性能有损。
- [Interpreter](https://github.com/Ismantic/Interpreter) 以Summer为底座，用SFT+DPO+GPRO方法训练得到的中英翻译模型。


基础库
- [Wavec](https://github.com/Ismantic/Wavec) 实现了经典的w2v方法，以及附带了实现Kmeans聚类，能作为Topic初始化用。
- [Semat](https://github.com/Ismantic/Semat) 实现了经典的LDA方法，用了分桶的技巧得以时间复杂度大幅降低。
- [Regex](https://github.com/Ismantic/Regex) 用状态机的方式实现的Regex引擎，支持了也许是用的最多的GPT-4 Pretoken正则。
- [Trie](https://github.com/Ismantic/Trie) 字典树是NLP领域最核心的数据结构，DoubleArrayTrie的基本实现。
- [UTF-8](https://github.com/Ismantic/Ustr) Unicode和UTF-8的编码方式讲解，以及简单的转化规则的代码实现。
- [Matx](https://github.com/Ismantic/Matx) Python -> C++ 的编译器实现，当前价值有限了。
- [Zero](https://github.com/Ismantic/Zero) 用C++实现了类似PyTorch的深度学习引擎实现，支持GPT模型的训练。


## 说明

这里的大多数项目仍在持续演进中。  
