# イラストで学ぶ 自然言語処理

<a href="https://www.kodansha.co.jp/book/products/0000430396"><img src="https://www.kspub.co.jp/book/detail/images/eb8935de89341542b36e828f67b3feaffdd695b7.jpg" alt="イラストで学ぶ 自然言語処理 大規模言語モデルへの最短コースの書影" width="200"></a>

『[イラストで学ぶ 自然言語処理 大規模言語モデルへの最短コース](https://www.kspub.co.jp/book/detail/5447208.html)』のサポートサイトです。

演習課題を実装したノートブックを公開しています。
コードや書籍の内容に関する質問は、[Issue](https://github.com/ryokan0123/nlp-illustrated/issues/new) にどうぞ。

## コード

各課題の「Open in Colab」から Google Colab で開き、上から順にセルを実行してください。
第1〜10章の演習ノートブックを公開しています。

| 章 | 課題 | Colab |
| --- | --- | --- |
| [第1章 自然言語処理の概要](01-nlp/README.md) | LLM にさまざまなタスクを解かせる | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/01-nlp/task1_various_tasks.ipynb) |
| [第2章 確率的言語モデルの基礎](02-language-modeling/README.md) | N-gram 言語モデルの実装 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/02-language-modeling/task1_ngram_lm.ipynb) |
| [第3章 トークン化の基礎](03-tokenization/README.md) | 異なるトークナイザの分割結果の比較 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/03-tokenization/task1_tokenizer_comparison.ipynb) |
|  | BPE の実装 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/03-tokenization/task2_bpe_implementation.ipynb) |
| [第4章 ニューラルネットワークの基礎](04-neural-network/README.md) | 勾配降下法による学習の実装 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/04-neural-network/task1_gradient_descent.ipynb) |
|  | ニューラル N-gram 言語モデルの学習 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/04-neural-network/task2_neural_ngram_lm.ipynb) |
| [第5章 Transformer](05-transformer/README.md) | Transformer の実装 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/05-transformer/task1_transformer_implementation.ipynb) |
|  | BERT による多義語の区別 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/05-transformer/task2_bert_polysemy.ipynb) |
| [第6章 アクセラレータと分散学習](06-distributed-learning/) | CPU と GPU の比較 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/06-distributed-learning/task1_cpu_gpu_comparison.ipynb) |
|  | データ並列の実装 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/06-distributed-learning/task2_data_parallel.ipynb) |
| [第7章 LLM の学習](07-llm-training/) | 指示チューニング | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/07-llm-training/task1_instruction_tuning.ipynb) |
| [第8章 LLM の推論と活用](08-llm-inference-and-application/) | Self-Consistency の効果検証 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/08-llm-inference-and-application/task1_self_consistency_verification.ipynb) |
|  | 外部ツールの統合 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/08-llm-inference-and-application/task2_external_tools_integration.ipynb) |
| [第9章 LLM の評価と安全性](09-llm-evaluation-and-safety/) | LLM-as-a-Judge による自動評価 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/09-llm-evaluation-and-safety/task1_llm_as_a_judge.ipynb) |
|  | レッドチーミング：架空の合言葉を聞き出そうとする実験 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/09-llm-evaluation-and-safety/task2_red_teaming.ipynb) |
| [第10章 マルチモーダル LLM](10-multimodal-llm/) | 視覚言語モデルによる画像質問応答 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokan0123/nlp-illustrated/blob/main/10-multimodal-llm/task1_vlm.ipynb) |

## リンク

- [Amazon](https://www.amazon.co.jp/dp/4065447208)
- [講談社](https://www.kodansha.co.jp/book/products/0000430396)
