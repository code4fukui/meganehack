# meganehack

[
![Website](https://img.shields.io/badge/website-live-brightgreen.svg)
](~~http://codeforfukui.github.io/meganehack~~ *(unavailable)*)

このリポジトリには、メガネハッカソンのWebサイトのソースコードが含まれています。これは、メガネやアイウェア技術のハックに焦点を当てたイベント用のJekyllベースのサイトです。

メガネハッカソンは、開発者、デザイナー、クリエイターが集まり、メガネに関連するあらゆるものを開発するイベントです。参加者は、メガネ自体を作ってもよし、メガネ型の最新デバイスで動くアプリやゲームを作ってもよし、メガネを新しくエキサイティングな方法で自由に「ハック」することができます。

<a href="http://codeforfukui.connpass.com/event/30182/" target="_blank">
    <img src="img/banner.png" alt="connpassで参加登録">
</a>

## イベント概要

- **テーマ**: メガネ自体の作成、スマートグラス用アプリの開発など、メガネに関連するあらゆるプロジェクトのためのハッカソン。
- **会場**: 日本の「メガネの聖地」である福井県鯖江市の嚮陽会館。
- **開催日時**:
  - 2016年5月28日(土) 10:20 - 17:00
  - 2016年5月29日(日) 10:20 - 16:00
- **参加方法**: [connpass](http://codeforfukui.connpass.com/event/30182/)での事前参加登録を推奨していますが、当日参加も受け付けています。

## 参加者向けリソース

クリエイティブなプロジェクトをサポートするため、さまざまなハードウェア、データ、素材が利用可能です:

- **メガネ型デバイス**:
  - MOVERIO BT-200
  - Vuzix M100
  - Sony Eyeglass
- **プロトタイピング用ハードウェア**:
  - こどもでも簡単にプログラミングができる [IchigoJam](http://ichigojam.net) コンピュータ。
  - ハードウェア類がその場で購入・利用可能な [スイッチサイエンス エイドステーション](https://www.switch-science.com/info/aidstation/)。
- **カスタムフレーム用3Dデータ**:
  - メガネフレーム「neo-plug」に結合可能なデバイスを作成するための3Dデータ。([詳細はこちら](http://fukuno.jig.jp/1270))
- **オープンデータ**:
  - [データシティ鯖江](http://data.city.sabae.lg.jp/)
  - [福井県オープンデータライブラリ](http://www.pref.fukui.lg.jp/doc/toukei-jouhou/opendata/)
  - [DATA.GO.JP](http://www.data.go.jp/)
  - [Open Data Platform (SPARQL)](http://sparql.odp.jig.jp/)
- **クリエイティブ素材**:
  - アイデア出しやプロトタイピングをサポートするペーパークラフト・アイデアシート。

## Webサイトの開発

このサイトはJekyllで構築されています。ローカルで実行するには以下の手順に従ってください:

1. リポジトリをクローンします。
2. 依存関係をインストールします:
    ```bash
    bundle install
    ```
3. Webサイトをローカルで起動します:
    ```bash
    bundle exec jekyll serve
    ```
4. ブラウザで `http://localhost:4000` を開きます。

## 運営

- **主催**: [Code for Fukui](http://fukui.opendata.cc)
- **協力**: [鯖江市](http://www.city.sabae.fukui.jp/)、[jig.jp co., ltd.](http://jig.jp/)

## ライセンス

このプロジェクトは MIT License の下でライセンスされています。詳細は [LICENSE](LICENSE) ファイルをご覧ください。
