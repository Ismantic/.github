# Ismantic

Ismantic 是一组围绕中文 NLP、文本处理、输入法和基础系统组件展开的实验性项目。

这些仓库大多采用同一种风格：
- 用尽量小而清晰的实现把核心原理直接写出来
- 关注可读性、可验证性和长期可维护性
- 尽量减少依赖，优先把问题本身讲清楚、做扎实

## 方向

- 中文分词与词表学习
- 输入法与语言模型
- Unicode / Trie / Regex 等基础文本组件
- 词向量、主题模型、序列标注
- 小型可读的机器学习与深度学习实现

## 项目

- [Iscut](https://github.com/Ismantic/Iscut)  
  基于 Double-Array Trie 的中文分词器，支持 DAG + DP 分词和无监督词频学习。

- [Sime](https://github.com/Ismantic/Sime)  
  面向长期演进的中文输入法实验项目。

- [Ustr](https://github.com/Ismantic/Ustr)  
  UTF-8 / Unicode 编解码与文本处理基础组件。

- [Trie](https://github.com/Ismantic/Trie)  
  多种 Trie 结构实现，包括 Double-Array Trie。

- [Regex](https://github.com/Ismantic/Regex)  
  从零实现的正则表达式引擎。

- [IsmaTokenizer](https://github.com/Ismantic/IsmaTokenizer)  
  BPE / SentencePiece 风格分词器实现。

## 说明

这里的大多数项目仍在持续演进中。  
如果你对中文 NLP、输入法、压缩数据结构，或者小而清晰的系统实现感兴趣，这里大概会有你想看的东西。
