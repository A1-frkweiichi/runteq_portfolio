# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- .....

\***\*README\*\***
■ サービス名
CREDO QUEST

■ サービス概要
RUNTEQ 生が CREDO をきっかけに上下垣根なく交流できるサービス

■ メインのターゲットユーザー
RUNTEQ 生

■ ユーザーが抱える課題
・リモート故、どんな人がいるかわかりにくい。交流するきっかけが少ない。
・カリキュラムが難しくなったり、仕事が忙しくなって、仲の良いひとがいないとフェードアウトしてしまう。
└ 毎月多くの入学生が増えるので、積極的に交流しないと知らない人が多数の状態に陥る。孤立感が強まる。

■ 解決方法
・同期生や先輩・後輩、スタッフがどんな性格をしている人か、性格診断 MAP（マトリックス表）に表示される。
・各ユーザページに、どんな性格をしている人か、得意なこと、褒められたら嬉しいポイントの傾向が掲載される。（12 種類に分類予定）
・各 CREDO、参考になる ToDo リストがある。他ユーザに NiceActive!!（いいね機能）と応援メッセージを送れる。

■ 実装予定の機能（以下の例は実際のアプリの機能から一部省略しています）
・性格診断テスト
├12 種類に分類
└ 性格診断 MAP・各ユーザページに結果表示
・性格診断 MAP（マトリックス表）
├ 各ユーザを表示、各ユーザページへ遷移できる
└ 各期、スタッフ、全体に絞り込みできる
・CREDO ToDo リスト
├ 各項目 10 段階にスモールステップ化（ToDo リスト）
├ チェック機能（済みになるとレベルが上がる）
└Twitter シェア機能
・NiceActive!!（いいね機能/CREDO 各 5 項目から選択）
├ 月 3 名まで制限（1 名につき 1 項目）
├ 他ユーザへメッセージを送れる（未記入可）
├ もらえたユーザはレベルが上がる
└Twitter シェア機能
・フォロー機能
└ 他ユーザページに遷移

■ なぜこのサービスを作りたいのか？
・忘れがちな CREDO をきっかけに、上下垣根なく交流できるきっかけを作りたい。
└ 仲の良い受講生ができると、学習が楽しくなる、励まし合えるなど、コミュニティのメリットが強まる。

■ スケジュール
企画〜技術調査：〜3/4
README〜ER 図作成：〜3/7
メイン機能実装：〜3/31
β 版を RUNTEQ 内リリース（MVP）：〜4/7
本番リリース：〜4/15

■ 画面遷移図
https://www.figma.com/file/AqBv01Dl4x37edQtdlpTR2/CREDO-QUEST?node-id=0%3A1&t=cMYdjAvrS3BGYooU-1
