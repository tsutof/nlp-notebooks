# nlp-notebooks
自然言語処理関連の Jupyter ノートブック コレクション

## 公開中のノートブック

| タイトル | ファイル | Google Colab | 技術記事リンク |
| --- | --- | --- | --- |
| LLM毎に最適化されたチャット プロンプトをテンプレートから効率的に作成する | [chat_prompt_template.ipynb](./chat_prompt_template.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tsutof/nlp-notebooks/blob/main/chat_prompt_template.ipynb) | [Zenn記事](https://zenn.dev/tsutof/articles/469cf3d1060e73) |
| 文章埋め込み表現をUMAPで可視化する | [umap_sentence_vector.ipynb](./umap_sentence_vector.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tsutof/nlp-notebooks/blob/main/umap_sentence_vector.ipynb) | [Zenn記事](https://zenn.dev/tsutof/articles/c6deea62e41dad) |

## ローカルで実行する方法

1. 本リポジトリをクローン
    ```
    git clone https://github.com/tsutof/nlp-notebooks
    cd nlp-notebooks
    ```

1. 必要により、Pythonの仮想環境を用意
    ```
    conda create --name nlp-notebooks python=3.10 --yes && \
    conda activate nlp-notebooks
    ```

1. JupyterLabをインストール
    ```
    python -m pip install --upgrade pip && \
    python -m pip install --no-cache-dir --upgrade jupyterlab ipywidgets
    ```

1. JupyterLabを起動
    ```
    jupyter lab
    ```

以上。
