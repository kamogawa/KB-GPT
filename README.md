# KB-GPT
### 仮想環境実行
```
python -m venv ./env 
pip install -r requirement.txt
source env/bin/activate
```

### langchaing とは
langchaingとは開発者が言語モデルを元にしたアプリケーションを作成する時、開発をしやすくするため設計されたフレームワークです。chatgptのような大規模言語モデル（LLM）を開発者が用意したロジックまたはデータと結合できるようにサポートしてくれます。これで拡張性と性能を持つAIアプリケーションが構築できます。

### Rag(Retrieval-Augmented Generation)
外部ソースから取得した情報を用いて、生成AIモデルの精度と信頼性を向上させるテクノロジです。LLMが回答を生成する際にユーザーの質問文に応じた知識情報を参照できるようにすることで、もっともらしい誤りを回答する「ハルシネーション（幻覚）」を防ぎます。