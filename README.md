# Zenn CLI

- [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)

## コマンド一覧

### 記事の新規作成

`npx zenn new:article`

```yaml
title: "" # 記事のタイトル
emoji: "😸" # アイキャッチとして使われる絵文字（1文字だけ）
type: "tech" # tech: 技術記事 / idea: アイデア記事
topics: [] # タグ。["markdown", "rust", "aws"]のように指定する
published: true # 公開設定（falseにすると下書き）
```

### 記事のプレビュー

`npx zenn preview`

## 記事の作成

個人的なメモです。

### 記事の公開

`published` オプションを `true` にします。

```md
published: true
```

### 記事の削除

削除はダッシュボードから行います。

### 画像の取り扱い

[🎆 GitHubリポジトリ連携で画像をアップロードする方法](https://zenn.dev/zenn/articles/deploy-github-images#%E7%94%BB%E5%83%8F%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%81%AE%E5%88%B6%E9%99%90%E4%BA%8B%E9%A0%85)
