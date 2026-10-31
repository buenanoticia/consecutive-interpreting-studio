# Consecutive Interpreting Studio (逐次通訳総合トレーナー)

国際会議通訳の認知モデル（ダニエル・ジルの認知負荷モデル、パリ学派の「意味の理論」・脱言語化、ロザンのノートテイキング7原則）に基づき、段階的に逐次通訳（Consecutive Interpreting）の技術を習得できるブラウザ完結型のトレーニングWebアプリケーションです。

🌐 **公開デモ (GitHub Pages)**: [https://buenanoticia.github.io/consecutive-interpreting-studio/](https://buenanoticia.github.io/consecutive-interpreting-studio/)

## 主な特徴

- **多言語スピーチ対応**: 台湾華語（繁體中文・ピンイン付き）、英語（English）、スペイン語（Español）の練習用スピーチ課題を内蔵。
- **Web Speech API 音声合成**: 再生速度（`0.75x` / `0.9x` / `1.0x` / `1.15x`）および再生単位（全文連続 / パラグラフ単位）を自在に切り替え可能。
- **自作スピーチ課題の追加**: ニュース原稿、YouTubeの文字起こし、EU Speech Repository などのスクリプトを貼り付けて、即座に4段階すべてのトレーニングに活用可能。
- **サーバー不要の単一HTML構成**: 外部バックエンドを必要とせず、PC・Mac・iPad・iPhoneのブラウザ上で軽快に動作。

## 4段階のトレーニング・カリキュラム

| ステージ | トレーニング手法 | 訓練の目的と主な機能 |
| :--- | :--- | :--- |
| **Stage 1** | **リテンション＆リプロダクション**<br>(Memory Without Notes) | ノートを取らずに音声を聴き、脳内に「情景（誰が・何を・どうしたか・数値）」を映像化（脱言語化 / Deverbalization）して保持する訓練。スクリプトの表示/非表示切替、コアメッセージ・数値・論理骨格の解答照合機能を搭載。 |
| **Stage 2** | **スラッシュ＆サイトラ（順送り訳）**<br>(Sight Translation) | SVO語順の外国語を後ろから返り読みせず、意味の切れ目（チャンク）ごとに前から順送りで日本語へ変換する訓練。自動チャンク送りペースメーカー（2.5秒 / 4.0秒 / 6.0秒）を搭載。 |
| **Stage 3** | **ロザン式ノートテイキング道場**<br>(Rozan Note-Taking Pad) | ジャン＝フランソワ・ロザンの7原則に基づく「左余白の接続詞（Link）」＋「S → V → O の階段配置（Shift）」を練習する専用ノートパッド。キーボード用の**構造化入力モード**と、iPad（Apple Pencil等）対応の**手書きペンモード**、頻出シンボルパレット、プロ通訳者の模範ノート比較機能を搭載。 |
| **Stage 4** | **実践逐次通訳＆セルフ評価**<br>(Full Consecutive & Critique) | 本番形式での逐次通訳と録音（MediaRecorder API）・再生レビュー。訳出テキストの必須キーワード自動判定機能と、ダニエル・ジルの「認知負荷モデル（Effort Models: `L + N + M + C`）」に基づくボトルネック自己診断ルーブリックを搭載。 |

## 理論的背景・参考文献

本ツールの設計は以下の通訳学・会議通訳指導の古典および標準テキストに基づいています。

- **Jean-François Rozan (1956)**: *La prise de notes en interprétation consécutive*（ノートテイキングの7原則：概念の記録、省略、論理接続 Links、否定、強調、縦の配置 Verticality、階段配置 Shift）
- **Andrew Gillies (2017)**: *Note-taking for Consecutive Interpreting: A Short Course (2nd Ed.)*, Routledge.
- **Daniel Gile (2009)**: *Basic Concepts and Models for Interpreter and Translator Training*, John Benjamins.（認知負荷モデル / Effort Models）
- **Danica Seleskovitch & Marianne Lederer (2014)**: *Interpréter pour traduire*, Les Belles Lettres.（意味の理論 / Théorie du Sens・脱言語化）
- **劉敏華 (2008)**: 『逐步口譯與筆記』書林出版.
- **小松達也 (2005)**: 『通訳の技術』研究社.

## 使い方・ローカル実行

1. **ブラウザから直接アクセス**:
   [https://buenanoticia.github.io/consecutive-interpreting-studio/](https://buenanoticia.github.io/consecutive-interpreting-studio/) を開きます（iPad / iPhone の Safari で「ホーム画面に追加」を行うと、フルスクリーンのWebアプリとして利用できます）。
2. **ローカルで開く場合**:
   リポジトリ内の `index.html`（または `consecutive_interpreting_studio.html`）をブラウザで直接開くだけで動作します。

## ライセンス

MIT License
