## Seq2Seq Introduction
### Questions
- How to process Variable length ?
- How to select top one with highest score ?


### Key Concepts
- Teacher Forcing
- Attention
- **[Beam Search][4]**
- Encoder-Decoder
- Embedding
- Fixed-Size Context vector(information bottleneck)
- **[Exposure Bias][3]**-Oracle


### Application
- 机器翻译
- 语音识别
- 文本摘要
- 问答系统
- 阅读理解
- [ChatBot][5]


### Reference Repo
- [**nmt**][9]


### Reference Blog
- [简说Seq2Seq原理及实现(含代码)][1]
- [CS224N(1.31) Translation, Seq2Seq, Attention][2]
- [Seq2Seq中Exposure Bias现象的浅析与对策][3]
- [**从语言模型到Seq2Seq：Transformer如戏，全靠Mask**][6]
- [**生成式对话seq2seq：从rnn到transformer**][7]
- [**神经机器翻译的训练改进和解码提速**][8]


[1]:https://zhuanlan.zhihu.com/p/57155059
[2]:http://bitjoy.net/2019/08/02/cs224n%ef%bc%881-31%ef%bc%89translation-seq2seq-attention/
[3]:https://zhuanlan.zhihu.com/p/128003099
[4]:https://zhuanlan.zhihu.com/p/28048246
[5]:https://pytorch.org/tutorials/beginner/chatbot_tutorial.html
[6]:https://zhuanlan.zhihu.com/p/84157931
[7]:https://zhuanlan.zhihu.com/p/97536876
[8]:https://mp.weixin.qq.com/s/CUHzCBfFGjATxEnpD1lhig
[9]:https://github.com/tensorflow/nmt