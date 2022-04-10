# SF創作講座 2022 梗概集

[ゲンロン 大森望 SF創作講座 2022](https://school.genron.co.jp/works/sf/2022/) 梗概集。

## 使い方

### 電子書籍のリリース

    $ git tag v1.0.0
    $ git push --tags

自動的に [Ebook ワークフロー](.github/workflows/ebook.yml)が起動し、makimonoを使ってビルドした電子書籍のリリースが行われます。

### 自動レビュー

Pull Requestを作成すると、[reviewdog ワークフロー](.github/workflows/reviewdog.yml)が起動し、textlintによる指摘が行われます。

## ライセンス

![クリエイティブ・コモンズ・ライセンス](https://i.creativecommons.org/l/by/4.0/88x31.png)

この作品は[クリエイティブ・コモンズ 表示 4.0 国際 ライセンス](http://creativecommons.org/licenses/by/4.0/)の下に提供されています。
