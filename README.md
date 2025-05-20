# 旋转位置编码下的情绪分类

本项目为数据科学相关课题开发，适用于学习与研究用途，禁止商业用途。  
如遇到问题，欢迎在 Issues 区留言。

---

## 目录结构与说明

### 根目录
- `README.md`：项目说明文件
- `数据科学结课作业.pdf`：结课作业报告
- `code/`：核心代码及数据
- `metrics/`：模型评估指标
- `pre trained model/`：预训练模型相关文件

---

### 1. code/
核心代码及数据集：

- [`bert.ipynb`](code/bert.ipynb)：正余弦位置编码 相关实验 Jupyter Notebook
- [`rope.ipynb`](code/rope.ipynb)：旋转位置编码 相关实验 Jupyter Notebook
- [`weibo_senti_100k.csv`](code/weibo_senti_100k.csv)：微博情感分析数据集


---

### 2. metrics/
模型评测数据与说明：

- [`bert_metrics.csv`](metrics/bert_metrics.csv)：BERT 模型实验结果
- [`rope_bert_metrics.csv`](metrics/rope_bert_metrics.csv)：ROPE-BERT 模型实验结果


---

### 3. pre trained model/
预训练模型相关文件：

- [`readme.md`](pre%20trained%20model/readme.md)：训练权重下载地址

---

## 使用说明

1. 克隆本仓库
    ```bash
    git clone https://github.com/Zhanli-Li/ROPE_BERT.git
    cd ROPE_BERT
    ```

2. 按需打开 `code/` 下的 Jupyter Notebook 文件，运行实验代码。
3. 评测结果请参考 `metrics/` 下的 CSV 文件。

---

## 许可与声明

- 本项目仅供学习和研究，禁止任何商业用途。
- 如需引用或改进，欢迎注明出处。

---

## 联系方式

如有疑问或建议，欢迎在 Issues 区留言。

项目主页：[Zhanli-Li/ROPE_BERT](https://github.com/Zhanli-Li/ROPE_BERT)
