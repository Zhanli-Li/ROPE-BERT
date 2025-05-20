# 旋转位置编码下的情绪分类 (Emotion Classification with Rotated Position Encoding)

本项目为数据科学相关课题开发，适用于学习与研究用途，禁止商业用途。  
如遇到问题，欢迎在 Issues 区留言。  
This project is related to data science and is developed for learning and research purposes only. Commercial use is prohibited.  
If you encounter any issues, feel free to leave a comment in the Issues section.

- 作者：[Zhanli Li / 李展利](https://zhanli-li.github.io/)  
- Author: [Zhanli Li / 李展利](https://zhanli-li.github.io/)
- 指导老师：[Xingyu Wang / 王新宇](https://wls.zuel.edu.cn/2022/0517/c3776a299072/page.htm)  
- Supervisor: [Xingyu Wang / 王新宇](https://wls.zuel.edu.cn/2022/0517/c3776a299072/page.htm)

---

## 目录结构与说明 (Directory Structure and Description)

### 根目录 (Root Directory)
- `README.md`：项目说明文件 (Project description file)
- `数据科学结课作业.pdf`：结课作业报告 (Final project report)
- `code/`：核心代码及数据 (Core code and data)
- `metrics/`：模型评估指标 (Model evaluation metrics)
- `pre trained model/`：预训练模型相关文件 (Pretrained model related files)

---

### 1. code/
核心代码及数据集 (Core code and dataset):

- [`bert.ipynb`](code/bert.ipynb)：正余弦位置编码相关实验 Jupyter Notebook (Experiments on Sine and Cosine Positional Encoding (Jupyter Notebook))
- [`rope.ipynb`](code/rope.ipynb)：旋转位置编码相关实验 Jupyter Notebook (Experiments on Rotated Positional Encoding (Jupyter Notebook))
- [`weibo_senti_100k.csv`](code/weibo_senti_100k.csv)：微博情感分析数据集 (Weibo sentiment analysis dataset)

---

### 2. metrics/
模型评测数据与说明 (Model evaluation data and description):

- [`bert_metrics.csv`](metrics/bert_metrics.csv)：BERT模型实验结果 (BERT model experiment results)
- [`rope_bert_metrics.csv`](metrics/rope_bert_metrics.csv)：ROPE-BERT模型实验结果 (ROPE-BERT model experiment results)

---

### 3. pre trained model/
预训练模型相关文件 (Pretrained model related files):

- [`readme.md`](pre%20trained%20model/readme.md)：训练权重下载地址 (Download link for training weights)

---

## 使用说明 (Usage Instructions)

1. 克隆本仓库 (Clone the repository)
    ```bash
    git clone https://github.com/Zhanli-Li/ROPE_BERT.git
    cd ROPE_BERT
    ```

2. 按需打开 `code/` 下的 Jupyter Notebook 文件，运行实验代码 (Open the Jupyter Notebook files under `code/` as needed, and run the experiment code).
3. 评测结果请参考 `metrics/` 下的 CSV 文件 (Refer to the CSV files under `metrics/` for evaluation results).

---

## 许可与声明 (License and Declaration)

- 本项目仅供学习和研究，禁止任何商业用途 (This project is for learning and research purposes only. Commercial use is prohibited).
- 如需引用或改进，欢迎注明出处 (If you wish to cite or improve the project, please acknowledge the source).

---

## 联系方式 (Contact Information)

如有疑问或建议，欢迎在 Issues 区留言 (If you have any questions or suggestions, feel free to leave a comment in the Issues section).

项目主页：[Zhanli-Li/ROPE_BERT](https://github.com/Zhanli-Li/ROPE_BERT)  
Project homepage: [Zhanli-Li/ROPE_BERT](https://github.com/Zhanli-Li/ROPE_BERT)
