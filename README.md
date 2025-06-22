# cat2151-zenn-contents

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
