# ItemEditor
アイテムのnbtデータをいじれるようにするPocketMine-MPプラグインです

## 導入方法
このプラグインを使用するには

- PocketMine-MP v4.*
- BboForm 2.*
  が必要になります。bboformは[こちら](https://github.com/bbo51dog/BboForm)からダウンロードが可能です

## コマンド

| Command | Permissions |
|---------|-------------|
| edit    | op          |

## 実装機能
- アイテムの名前、説明、個数を編集
  - アイテムの説明では\nで改行できます
  - また、入力しない場合は編集しないようになっています
- CompoundTagを編集
  - IntTag,FloatTag,StringTagを追加可能
  - 一度に複数のTag追加にも対応しています
- 道具の耐久値を有限又は無限に

## 注意事項  
コードは大変汚いため心優しい方がもし居らっしゃいましたらアドバイスやプルリクエストをお願いします
