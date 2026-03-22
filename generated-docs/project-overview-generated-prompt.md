Last updated: 2026-03-23


# プロジェクト概要生成プロンプト（来訪者向け）

## 生成するもの：
- projectを3行で要約する
- プロジェクトで使用されている技術スタックをカテゴリ別に整理して説明する
- プロジェクト全体のファイル階層ツリー（ディレクトリ構造を図解）
- プロジェクト全体のファイルそれぞれの説明
- プロジェクト全体の関数それぞれの説明
- プロジェクト全体の関数の呼び出し階層ツリー

## 生成しないもの：
- Issues情報（開発者向け情報のため）
- 次の一手候補（開発者向け情報のため）
- ハルシネーションしそうなもの（例、存在しない機能や計画を勝手に妄想する等）

## 出力フォーマット：
以下のMarkdown形式で出力してください：

```markdown
# Project Overview

## プロジェクト概要
[以下の形式で3行でプロジェクトを要約]
- [1行目の説明]
- [2行目の説明]
- [3行目の説明]

## 技術スタック
[使用している技術をカテゴリ別に整理して説明]
- フロントエンド: [フロントエンド技術とその説明]
- 音楽・オーディオ: [音楽・オーディオ関連技術とその説明]
- 開発ツール: [開発支援ツールとその説明]
- テスト: [テスト関連技術とその説明]
- ビルドツール: [ビルド・パース関連技術とその説明]
- 言語機能: [言語仕様・機能とその説明]
- 自動化・CI/CD: [自動化・継続的統合関連技術とその説明]
- 開発標準: [コード品質・統一ルール関連技術とその説明]

## ファイル階層ツリー
```
[プロジェクトのディレクトリ構造をツリー形式で表現]
```

## ファイル詳細説明
[各ファイルの役割と機能を詳細に説明]

## 関数詳細説明
[各関数の役割、引数、戻り値、機能を詳細に説明]

## 関数呼び出し階層ツリー
```
[関数間の呼び出し関係をツリー形式で表現]
```
```


以下のプロジェクト情報を参考にして要約を生成してください：

## プロジェクト情報
名前: cat2151-zenn-contents
説明: # cat2151-zenn-contents

## これはなに？
- Zennへの投稿の草稿を `published: false` で版管理する用です。
- `published: true`で投稿したあとも、記事修正を版管理するつもりです。
- 無料記事をpublicリポジトリで版管理します。
- 詳しくは:
    - [GitHubリポジトリでZennのコンテンツを管理する](https://zenn.dev/zenn/articles/connect-to-github)
    - [ZennとGithubを連携する方法](https://zenn.dev/eguchi244_dev/articles/github-zenn-linkage-20230501)

## 自分用メモ:
### なぜZennで書くか？:
- [そのアプリをぐぐって探している人に届ける用。GitHubプロジェクトがマイナーだとGoogle検索にヒットしないが、Zennに書けばヒットするので。](https://zenn.dev/cat2151/scraps/8e0e950ed2888e)
### 書く記事の候補を洗い出す:
- ※ブレインストーミング的
- 音楽関連
    - 案、用途別、アプリやライブラリ一覧、2024年版、ブラウザ、ネイティブ
        - 例、Tone.jsは、ブラウザ、ライブラリ、Web Audio
        - 備忘、既存の有用な記事へのリンクも
            - 例、web audio library でぐぐって見つけたこれ [GitHub - notthetup/awesome-webaudio: A curated list of awesome WebAudio packages and resources.](https://github.com/notthetup/awesome-webaudio?tab=readme-ov-file)
                - 案、むしろこれを紹介する記事もアリでは
        - 備忘、検索キーワードの例示も、例えばWeb Audio Library
    - postmate-midi 今後リポジトリ作成予定
    - oscsync for browser 今後リポジトリ作成予定
    - Web MIDI API 関連
    - Web Audio API 関連
    - MML 関連
- Obsidian関連
    - Obsidianと音楽
        - [MMLやコード進行を書けるコミュニティプラグインを作った](https://github.com/cat2151/obsidian-plugin-mmlabc)
    - Obsidian全般
        - [recursive-folding コミュニティプラグインを作った](https://github.com/cat2151/recursive-folding)
        - [使っているホットキー一覧](https://zenn.dev/cat2151/scraps/9e98348dfcd168)
        - [ざっくりTIPS](https://zenn.dev/cat2151/scraps/926fd3596dddda)
        - [CSSスニペットを書いた](https://zenn.dev/cat2151/scraps/a7777518246458)

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


依存関係:
{
  "dependencies": {
    "zenn-cli": "^0.4.6"
  },
  "devDependencies": {}
}

## ファイル階層ツリー
📄 .gitignore
📖 README.md
📄 _config.yml
📁 articles/
  📄 .keep
  📖 github-zenn-linkage-20240217.md
  📖 github-zenn-linkage-20260316.md
📁 books/
  📄 .keep
📁 generated-docs/
📊 package-lock.json
📊 package.json

## ファイル詳細分析


## 関数呼び出し階層
関数呼び出し階層を分析できませんでした

## プロジェクト構造（ファイル一覧）
README.md
articles/github-zenn-linkage-20240217.md
articles/github-zenn-linkage-20260316.md
package-lock.json
package.json

上記の情報を基に、プロンプトで指定された形式でプロジェクト概要を生成してください。
特に以下の点を重視してください：
- 技術スタックは各カテゴリごとに整理して説明
- ファイル階層ツリーは提供された構造をそのまま使用
- ファイルの説明は各ファイルの実際の内容と機能に基づく
- 関数の説明は実際に検出された関数の役割に基づく
- 関数呼び出し階層は実際の呼び出し関係に基づく


---
Generated at: 2026-03-23 07:03:58 JST
