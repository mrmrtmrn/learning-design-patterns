# learning-design-patterns

GoFのデザインパターンを、書籍を参考にしながらJava・Rubyで実装して学ぶリポジトリ。

## 参考書籍

- Java言語で学ぶデザインパターン入門 第3版（結城 浩 / SBクリエイティブ）

## 実行環境

- Docker（Java / Ruby それぞれのコンテナを用意）
- ローカルのソースコードをボリュームマウントして、コンテナ内で実行する構成

## 使い方

プロジェクトルートで実行すること。

```bash
# Java
./run java/iterator/Iterator.java

# Ruby
./run ruby/iterator/iterator.rb
```

## ディレクトリ構成

```
learning-design-patterns/
├── index.md
├── docker-compose.yml
├── run                    # 実行用スクリプト
├── java/
│   └── iterator/          # パターンごとにディレクトリ
│       └── Iterator.java
└── ruby/
    └── iterator/
        └── iterator.rb
```
