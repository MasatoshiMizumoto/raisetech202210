# 第12回課題報告

## 設計

### やること

- CircleCIにServerSpecとAnsibleの処理を追加する
  - 1）Cfnのテスト
    - taskcatで
  - 2）ServerSpecは何をテストする？
    - SSHで
      - configの展開が必要
      - 公開鍵のプロジェクト埋め込みが必要
    - ポートのリッスン
    - パッケージインストールチェック
  - 3）Ansibleは？
    - yum
    - ruby/rbenv
    - node/yarn
    - fetch code
    - rails
      - development.rb
      - database.yml
      - precompile
      - rails

### やらないこと
