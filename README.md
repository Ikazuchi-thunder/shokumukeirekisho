# 履歴書・職務経歴書

poem/mixchannel.md は、最初の転職のときに転職ドラフトに登録したレジュメです。

## 基本情報

### なまえ

大井 愛仁（おおい　あきひと）

### 生年月日

1992 年 7 月 21 日

### 連絡先

- ikazuchisdiary@gmail.com
- https://www.facebook.com/ikazuchisdiary/
- https://twitter.com/Ikazuchis_diary

## 学歴・職歴

| 年月                          | 所属                                     |
| ----------------------------- | ---------------------------------------- |
| 2011 年 4 月 - 2015 年 3 月   | 京都大学工学部情報学科                   |
| 2015 年 4 月 - 2017 年 3 月   | 京都大学大学院情報学研究科社会情報学専攻 |
| 2017 年 4 月 - 2018 年 11 月  | 株式会社 Donuts                          |
| 2018 年 12 月 - 2019 年 10 月 | 株式会社サイバーエージェント             |
| 2019 年 11 月 - 現在          | 株式会社 toridori                        |

## 得意なシチュエーション

- プロダクト面
  - プロダクトマネージャ等と相談して、提案された機能を実装面やその実装に意味があるかを考え、案を修正する
  - ブレインストーミング等で得られた抽象的な意見を整理し、施策に落とす
  - （特に抽象的な要望に対して、）判断に必要な適切なデータを取得・可視化する
  - sklearn 等を用いる、基本的な機械学習を用いたデータ処理
- 実装面
  - レコメンド基盤の実装・運用
  - 基本的なサーバサイド実装

## 触れたことのある言語等

| 概要               | 詳細                                                 |
| ------------------ | ---------------------------------------------------- |
| 言語               | Python, Go, Java, Ruby, TypeScript 等                |
| Web フレームワーク | gRPC, Spring Boot, echo, Flask, Vue.js 等            |
| 分析系             | Pandas, JupyterLab, Scikit-learn, Keras, BigQuery 等 |
| OS                 | Windows, Mac, Linux                                  |

## 職歴

### 2019 年 11 月- 株式会社 toridori

5 ～ 8 人程度の開発部に所属

レコメンド基盤開発・データ解析を基本に行っているが、Web フロント、サーバを触る場合もある。

#### toridori base レコメンド基盤開発

toridori base というスマートフォンアプリ向けの、レコメンド基盤の開発

- 使用技術
  - Python(バッチ処理)
  - Go
    - gRPC
  - Vue.js（管理画面）
- 概要
  - バッチ処理を定期実行し、S3 にアップロード
  - サーバで S3 のデータを取得し、gRPC で API サーバに送信
  - 管理画面上で設定や A/B テスト等の管理が可能

#### toridori base ダッシュボード開発

toridori base のダッシュボードを作った

- 使用技術
  - Google Data Portal
  - SQL とか
- 概要
  - toridori base の KPI が自動的に Slack に送られる

#### toridori Ad ダッシュボード開発

toridori Ad のダッシュボード作った

- 使用技術
  - Vue.js, Chart.js
- 概要
  - toridori Ad のインフルエンサーのステータスが見れる

#### データ取得・分析・可視化

toridori のすべてのプロダクトに対して、データ取得・分析・可視化

- 使用技術
  - Python
    - JupyterLab
    - Pandas
    - Scikit-Learn
    - xgboost
    - seaborn
    - など
  - MySQL
  - Google BigQuery
- 概要
  - KPI 異常があったときに調べるとか
  - 営業の仮説を検証するとか
  - 日々データに触れるようにしています

### 2018 年 12 月 - 2019 年 10 月 株式会社サイバーエージェント

秋葉原ラボに所属、2 名で Ameba Blog アプリのレコメンドを開発

#### Ameba Blog アプリレコメンドシステム

Ameba Blog アプリのフィードに流すブログをセレンディピティ等も考慮して決めるシステム

- 使用技術
  - Java
    - SpringBoot
  - Python
    - 実験用
- 概要
  - アプリリニューアルと同時だったため、どのようなものが流れるべきかから深く検討
  - 実装は、社内基盤を拡張する形
  - YouTube のレコメンドを目指すような形

### 2017 年 4 月 - 2018 年 11 月 株式会社 Donuts

10 人程度の MixChannel チームに所属

#### MixChannel レコメンドシステムの開発

MixChannel の動画やライブをレコメンドするシステムの開発

- 使用技術
  - Python（サーバ・バッチともに）
    - Flask -> gRPC
- 概要
  - 動画・ライブを推薦
  - 当初は Flask で配信していたが、gRPC に変更
  - バッチで計算したデータを Pickle 化してサーバに送信
  - より詳細は poem/mixchannel.md に

#### MixChannel API サーバ開発

ヘルプ的に MixChannel の API サーバ開発を手伝った

- 使用技術
  - Go
    - echo
- 概要
  - イベント用 API サーバを 1 から立てた
  - 参加者の獲得ポイントランキングを送信

#### MixChannel iOS アプリ開発

MixChannel の iOS アプリ実装を手伝った

- 使用技術
  - Swift
- 概要
  - レコメンド表示部分のみ
  - 1 週間程度のみの開発だったが、アプリ実装の基本が知れてよかった

#### データ取得・分析・可視化

MixChannel のデータ取得・分析・可視化

- 使用技術
  - Python
    - JupyterLab
    - Pandas
    - Scikit-Learn
    - xgboost
    - seaborn
    - など
  - MySQL
  - Google BigQuery

#### 新卒研修

完結したスマートフォンゲームを作る

- 使用技術
  - Unity
