---
language:
- zh
- en
tags:
- offline RL
- decision transformer
---
# Decision Transformer
<p align="center">
   🌐 <a href="https://chatglm.cn/blog" target="_blank">Blog</a> • 💻 <a href="https://github.com/THUDM/ChatGLM-6B" target="_blank">Github Repo</a> • 🐦 <a href="https://twitter.com/thukeg" target="_blank">Twitter</a> • 📃 <a href="https://arxiv.org/abs/2103.10360" target="_blank">[GLM@ACL 22]</a> <a href="" target="_blank">[GitHub]</a> • 📃 <a href="https://arxiv.org/abs/2210.02414" target="_blank">[GLM-130B@ICLR 23]</a> <a href="https://github.com/THUDM/GLM-130B" target="_blank">[GitHub]</a> <br>
</p>



**我们发布了decision transformer的模型配置 来训练在openAI的环境中的智能体。
注意在导入D4RL库的时候需要重启COLAB，第一次导入的时间较长需要耐心等待。开



## 软件依赖

```shell
各种依赖见ipynb的文件
```

## 代码调用 



```ipython

晚上睡不着可能会让你感到焦虑或不舒服,但以下是一些可以帮助你入睡的方法:

1. 制定规律的睡眠时间表:保持规律的睡眠时间表可以帮助你建立健康的睡眠习惯,使你更容易入睡。尽量在每天的相同时间上床,并在同一时间起床。
2. 创造一个舒适的睡眠环境:确保睡眠环境舒适,安静,黑暗且温度适宜。可以使用舒适的床上用品,并保持房间通风。
3. 放松身心:在睡前做些放松的活动,例如泡个热水澡,听些轻柔的音乐,阅读一些有趣的书籍等,有助于缓解紧张和焦虑,使你更容易入睡。
4. 避免饮用含有咖啡因的饮料:咖啡因是一种刺激性物质,会影响你的睡眠质量。尽量避免在睡前饮用含有咖啡因的饮料,例如咖啡,茶和可乐。
5. 避免在床上做与睡眠无关的事情:在床上做些与睡眠无关的事情,例如看电影,玩游戏或工作等,可能会干扰你的睡眠。
6. 尝试呼吸技巧:深呼吸是一种放松技巧,可以帮助你缓解紧张和焦虑,使你更容易入睡。试着慢慢吸气,保持几秒钟,然后缓慢呼气。

如果这些方法无法帮助你入睡,你可以考虑咨询医生或睡眠专家,寻求进一步的建议。
```

关于更多的使用说明，包括如何运行命令行和网页版本的 DEMO，以及使用模型量化以节省显存，请参考我们的 [Github Repo](https://github.com/THUDM/ChatGLM-6B)。

For more instructions, including how to run CLI and web demos, and model quantization, please refer to our [Github Repo](https://github.com/THUDM/ChatGLM-6B).

## Change Log
* v1.1.0 ([942945d](https://huggingface.co/THUDM/chatglm-6b/commit/942945df047dee66f653c68ae0e56655045f1741)): 更新 v1.1 版本 checkpoint
* v0.1.0 ([f831824](https://huggingface.co/THUDM/chatglm-6b/commit/f83182484538e663a03d3f73647f10f89878f438))

## 协议

本仓库的代码依照 [Apache-2.0](LICENSE) 协议开源.

## 引用

如果你觉得我们的工作有帮助的话，请考虑引用下列论文：

