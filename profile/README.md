# 是语实验室
- **底层实现**：深度剖析语言技术的不同环节，交付代码库和文档；
- **低成本实践**：以有限资源交付出有实际应用价值的模型和应用；


以下是项目介绍：

## 三本书

三本书的源码统一维护在
[IsBook](https://github.com/Ismantic/IsBook)，记录语言技术的底层实现。

- [Text：文本处理](https://ismantic.github.io/text)
  从 Unicode、UTF-8 和正则表达式出发，实现 Trie、中文分词与 Tokenizer。
- [Zero：训练引擎](https://ismantic.github.io/zero)
  从张量和自动微分出发，实现模型训练、GPU 计算与 GPT。
- [Matx：编译器](https://ismantic.github.io/matx)
  从 AST 和 Visitor 出发，实现运行时对象、容器、函数与 FFI。

## 两套模型

### BERT

- [BERTc](https://github.com/Ismantic/BERTc)：改进 BERT 模型结构，并实践
  CWS、NER、POS 与文本纠错等Character分类任务。
- [Wapic](https://github.com/Ismantic/Wapic)：将泛化能力更强的 BERT 模型
  蒸馏为更轻、更快的 CRF 模型。

### GPT

- [Summer](https://github.com/Ismantic/Summer)：类似 NanoChat，不过增加了对中文语料的处理，以及 ReTok 的支持。
- [Interpreter](https://github.com/Ismantic/Interpreter)：在 Summer 基础上
  结合 SFT、CPO 与 GRPO 训练中英翻译模型。

## 两个产品

### 是语输入法

以本地统计语言模型为核心，支持简繁、中英、全拼、简拼和九宫格输入。

- [SimeApp](https://github.com/Ismantic/SimeApp)：Android、macOS 与
  Linux/Fcitx5 输入法应用。
- [Sime](https://github.com/Ismantic/Sime)：C++ 输入法引擎、语言模型与训练工具。
- [DictCut](https://github.com/Ismantic/DictCut)：面向输入法语料的 EM
  中文分词实现。
- [Handwritten](https://github.com/Ismantic/Handwritten)：为输入法补充手写
  汉字识别能力的 MobileNet-v2 模型。

### 是语人物志

- [IsEntity](https://github.com/Ismantic/IsEntity)：基于维基数据和维基百科，
  使用强类型 Scheme Entity 组织人物知识。

