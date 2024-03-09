# nlp-notebooks
自然言語処理関連の Jupyter ノートブック コレクション

## 公開中のノートブック

| タイトル | ファイル | 内容 | Google Colab | 技術記事リンク |
| --- | --- | --- | --- | --- |
| 文章ベクトルの可視化 | [umap_sentence_vector.ipynb](./umap_sentence_vector.ipynb) | livedoorニュースコーパスの文章ベクトルをUMAPで可視化する | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tsutof/nlp-notebooks/blob/main/umap_sentence_vector.ipynb) | |

## ローカルで実行する方法

```
conda create --name nlp-notebooks python=3.10 --yes && \
conda activate nlp-notebooks
```

```
python -m pip install jupyterlab ipywidgets
```

```
jupyter lab
```