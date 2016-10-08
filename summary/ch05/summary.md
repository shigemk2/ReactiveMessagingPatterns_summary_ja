## ch05 Messaging Channels
### Point-to-Point Channel

- メールボックス
    - FIFO
- メッセージ処理はシーケンシャル

### Publish-Subscribe Channel

- パブ/サブの2種類のチャネルがある
- GOFでいうところのオブザーバーパターン

### Datatype Channel

- データ型に対応したチャネル

### Invalid Message Channel

- 受け手が理解できないメッセージを投げられた時に対応したチャネル

### Dead Letter Channel

- actor systemがレシーバーにメッセージを送信できない場合に対応したチャネル

### Guaranteed Delivery

- 通常actorはメッセージの送信を保証しないが、メッセージ送信を保証するチャネル

### Channel Adapter

- TODO

### Message Bridge

- アプリケーション間のメッセージのやりとり
    - JMS
    - RabbitMQ

### Message Bus

- さらに多くのシステムとメッセージのやりとりをしないといけないとき

