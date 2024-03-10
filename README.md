# nlp-notebooks
自然言語処理関連の Jupyter ノートブック コレクション

## 公開中のノートブック

| タイトル | ファイル | Google Colab | 技術記事リンク |
| --- | --- | --- | --- |
| 文章埋め込み表現をUMAPで可視化する | [umap_sentence_vector.ipynb](./umap_sentence_vector.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tsutof/nlp-notebooks/blob/main/umap_sentence_vector.ipynb) | |

## ローカルで実行する方法

```
conda create --name nlp-notebooks python=3.10 --yes && \
conda activate nlp-notebooks
```

```
python -m pip install --upgrade pip && \
python -m pip install --no-cache-dir --upgrade jupyterlab ipywidgets
```

```
jupyter lab
```