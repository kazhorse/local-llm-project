# local-llm-project

ローカルLLMを用いたRAG構成の検証および、RAGASによる定量評価を行う実験用リポジトリ。

## 内容
- テキストのチャンク化・ベクトル化ノートブック
- 複数Embeddingモデルの比較
- RAGAS による評価  
  - Faithfulness  
  - Answer Relevancy  
  - Context Precision  
  - Context Recall  

## 使い方（GPTは自分で）
- 評価用の質問生成、回答の解釈、考察は GPT を用いて実施
- RAGAS の各指標は GPT による判定結果を前提としている
- プロンプト設計および評価観点は実験目的に応じて調整する
