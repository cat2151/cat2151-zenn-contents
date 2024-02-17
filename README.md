# cat2151-zenn-contents

## これはなに？
- Zennへの投稿の草稿を `published: false` で版管理する用です。
- `published: true`で投稿したあとも、記事修正を版管理するつもりです。
- 無料記事をpublicリポジトリで版管理します。
- 詳しくは:
    - [GitHubリポジトリでZennのコンテンツを管理する](https://zenn.dev/zenn/articles/connect-to-github)
    - [ZennとGithubを連携する方法](https://zenn.dev/eguchi244_dev/articles/github-zenn-linkage-20230501)

## 自分用メモ:
### Zenn CLI
* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)

#### 新たに草稿を書く場合の例:
```sh
npx zenn new:article --slug github-zenn-linkage-20240217
```

#### 草稿をプレビューする場合は:
```sh
npx zenn preview
```
