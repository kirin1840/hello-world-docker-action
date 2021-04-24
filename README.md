# hello-world-docker-action
execute docker container by github action 

# Hello world docker action

このアクションは"Hello World"もしくは"Hello" + ログに挨拶する人物名を出力します。

## 入力

### `who-to-greet`

**必須** 挨拶する相手の名前。 デフォルトは `"World"`。

## 出力

### `time`

挨拶した時刻。

## 使用例

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'User Name'


## 仕組み
main.yml のワークフローにて、action.hmlを実行

