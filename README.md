# nlp-notebooks
自然言語処理関連の Jupyter ノートブック コレクション

## 公開中のノートブック

| タイトル | ファイル | 内容 | Colab | 技術記事リンク |
| --- | --- | --- | --- | --- |
| 文章ベクトルの分布を可視化 | [umap_sentence_vector.ipynb](./umap_sentence_vector.ipynb) | livedoor ニュースコーパスを使って、文章ベクトルの分布をUMAPで可視化する | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tsutof/nlp-notebooks/blob/main/umap_sentence_vector.ipynb) | |

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