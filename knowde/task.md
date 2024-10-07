# 記述支援 入力を進めるに際してのサポート
  知識の登録時に紐付けの抜け漏れがないか診断したい

## 永続化
  CollectionRepo: 永続化の汎用部品
    e.g. ListRepo, SetRepo, DictRepo
  DBに依存しない形、プレーンテキストの読み書きだけでも
    全てのストーリーが実現できるはず
  load プレーンテキストからメモリへ読み取る
  save メモリ上のデータを永続化する
  eat プレーンテキスト->メモリ->DB
  primitive テキストとしての表現を持つ
    namespace
    name
    scope: インデントの単位
  InMemory in /complex primitiveの複合, saveできる

TODO:
-[ ] "="を使えるようにする

# WANT やりたい
  knowde.vim vimでの補完
  article: .mdの自動生成と連動するデータ単位
    ブログの自動生成
  知識を増やす喜び、育成ゲーム

