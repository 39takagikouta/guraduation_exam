# [schedule sharing 　-スケジュールをシェアして行動を習慣化しよう-]

## サービス概要

本サービスは生活習慣の習慣化に苦心するランテック生を対象にした、習慣化をサポートするためのスケジュール管理 × コミュニティ形成アプリです。
基本は普通のスケジュール管理アプリですが、特徴はスケジュールをシェアできる事です。時間自体をシェアして同時に行うのも良いし、タスクのみをシェアしてそれぞれが別々の時間に行っても良いです。
習慣化は強制力とモチベーション維持が大事だと考えます。スケジュールの一部をシェアし、同じ目標の誰かと集まってそれを行うことで、両者を満たせるのではないかと考えました。

##　想定されるユーザー層
生活習慣（早寝早起き、勉強、筋トレ等）の習慣化に苦心しているランテック生

## サービスコンセプト

- ユーザーが抱えている課題感と提供するサービスでどのように解決するのか
  生活習慣（早寝早起き、勉強、筋トレ等）の習慣化に苦心している生徒が多いと考える。
  例えば、RUNTEQ 生活は長期戦であるため、学習の習慣化が大切だが、私自身これはなかなか難しかったし、Twitter でこれに苦心している方をよく見かける。
  そこで、サービス概要で述べたようなスケジュール管理 × コミュニティ形成アプリという形でそれを解決できるのではないかと考えた。
  本サービスで、強制力とモチベーション維持ができる機構を作りたいと思っている。習慣化に必要な要素はこの二つであると考えるからだ。
  まず、強制力について説明する。
  私の経験なのだが、何らかの生活習慣（生活リズム固定、勉強、筋トレなど）の習慣化には実行時間をある程度固定することが有効だと考え、1 日や 1 週間の計画を立てるのだが、予定を立てて満足してしまい、実行できないことが何度もあった。
  予定を紙やスマホのメモに書いていたのだが、それらには実行を強制する機能がついていないので、計画と強制力による実行支援（Twitter に内容を簡単に投稿でき、周囲に宣言できる、適宜通知でスケジュールをリマインドして行動にはっぱをかけてくれる等）を一つのアプリでできれば解決できると考えた。
  また、スケジュールをシェアして誰かと一緒に行うことで、ピアプレッシャー（共通の立場に置かれた仲間集団からの圧力の名称）を発生させることができると考えた。
  次に、モチベーション維持である。行動を決まった時間に行えたとしても、内容が苦痛で本人がへばってしまったら意味がない。
  スケジュールをシェアすることで人との繋がりを感じることで、モチベーションが維持できるのではないかと考えた。もちろん、知識をシェアすることもできる。
  ゆくゆくは AI による計画の立案支援や 1 日のフィードバック、褒め言葉の提供によるモチベートの機能も追加して、強制力とモチベーション維持をもっと高い水準で行えたら良いと考える。

- なぜそのサービスを作ろうと思ったのか
  RUNTEQ 生の離脱率を下げるアプリを作成したいと考えたから。
  私はコミュニティリーダーだったのだが、能力が低くあまり同期をモチベートすることができなかったため、結果的に比較的離脱者が多めの期になってしまったように感じる。
  また、私自身も離脱しかけたのだが、他の生徒さんに助けていただいた。
  このことから、コミュニティリーダーとして不甲斐なかったことの後悔と、RUNTEQ コミュニティに恩返ししたいという気持ちがあり、RUNTEQ 生の離脱率を下げるアプリを開発したいと考えた。

- どこが売りになるか、差別化ポイントになるか
  スケジュール管理がそのままコミュニティ形成（Twitter で募集できるため、近くの人と繋がりやすい）に繋がり、習慣化のための強制力とモチベーション維持を一度に行える点
  また、予定と実行結果の記録と投稿、実行支援、振り返り等のスケジュール管理を一つのアプリで行える点

## 実装を予定している機能

### MVP

- 会員登録
- ログイン
- スケジュール管理機能
  - 1 日、1 週間のスケジュール設定機能（内容を Twitter で呟くことができる）
  - 1 日、1 週間のスケジュール振り返り機能（内容を Twitter で呟くことができる）
  - 通知によるスケジュール実行促進機能
  - スケジュール公開機能（任意）
  - 過去のスケジュールと実行結果、振り返りのログ機能
- コミュニティ形成機能
  - スケジュールシェア募集機能（任意。また、内容を Twitter で呟くことができる）
  - スケジュールシェア申請機能
  - スケジュールシェアによるグループ一覧機能（表示は任意）
  - シェアグループ内でのチャット機能
  - シェアグループ内での目標設定、進捗管理機能
  - シェアのスタイルは同期（時間をシェアして同じ時間で同じタスクを行う）か非同期（タスクのみをシェアして実行結果のみ報告し合う）を選択できる
- その他の機能
  - 簡単な自己紹介機能（交流にあたって、事前にその人のある程度の人格や状況を把握できるため、具体的な項目は、年齢（任意）、何期か、趣味、フルコミットか働きながらか、カリキュラムの進度くらいの項目があれば十分）

### その後の機能

- AI でスケジュールの提案、スケジュール実行結果に対するフィードバックをくれたり、褒めたり励まじたりしてくれる機能
- 特定のユーザーをブロックできる機能
- グループのチャット機能を LINE のグループ機能と連携することができる機能
- ポモドーロ機能
- 他のカレンダーアプリとの同期
