## ch05 Messaging Channels
### Point-to-Point Channel

- メールボックス
    - FIFO
- メッセージ処理はシーケンシャル

### Publish-Subscribe Channel

- パブ/サブの2種類のチャネルがある

### Datatype Channel

- データ型に対応したチャネル

### Invalid Message Channel

- 受け手が理解できないメッセージを投げられた時に対応したチャネル

### Dead Letter Channel

- actor systemがレシーバーにメッセージを送信できない場合に対応したチャネル

