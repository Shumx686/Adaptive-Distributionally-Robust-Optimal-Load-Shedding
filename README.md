# 完整研究代码与实验结果

对应论文 **Adaptive Distributionally Robust Optimal Load Shedding in Wind-Integrated Power Systems**。

下载 **[Code.zip](Code.zip)** 并解压。包内完整保留复现需要的代码、固定配置、逐情景结果、验证候选输出、历史逐小时记录、求解迭代，以及当前稿件使用的风电压力和敏感性实验材料。

`FILE_GUIDE.md`解释各类文件用途，`file_inventory.csv`逐个列出文件路径、大小和用途。论文正文、参考文献库、投稿附件、缓存与本地排版检查材料不在代码包内。结果图作为研究结果保留。

从解压后的 `segan-code` 目录开始：

```sh
python -m pip install -r requirements.txt
python reproduce.py verify
python reproduce.py figures
python reproduce.py reports
```

更多完整实验与敏感性结果的复算命令见包内中英文README和 `supplementary_studies/README.md`。重新求解需Julia及原始第三方输入；输入来源、精确文件名和校验值均有说明。

本仓库中的ZIP作为完整下载包保存，运行前需要解压。

Windows建议解压到较短的位置，如 `D:/segan-code`，再执行复现命令。
