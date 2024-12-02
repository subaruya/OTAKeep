## サービス名

未定


## サービス概要

このサービスはキャラクターグッズの予約情報を管理するWebアプリです。
予約開始待ちの欲しいグッズや予約済グッズの名前や予約日、予約サイト、発売予定日を記録・検索でき、予約忘れ・重複注文の防止や管理のサポートをすることを目的としています。


## このサービスへの思い・作りたい理由

キャラクターグッズとその予約に関する情報を一元管理できるツールが欲しいという思いから本サービスの着想を得ました。
アクリルスタンドや缶バッジ、フィギュアなど、俗に「オタクグッズ」と呼ばれるキャラクターグッズの多くは受注生産品となっています。入手には事前予約が求められるとともに、予約から発売まで数ヶ月〜長ければ1年もの期間が空くこともあります。
また、複数の通販サイトで同一商品の予約を取り扱っていることも多いです。
予約開始前のグッズについては「予約期間がいつの間にか終わってしまっていた」、既に予約したグッズについては「予約したことを失念していて重ねて予約してしまったり、同じグッズを別々の通販サイトで予約してしまったりして、届いてから重複注文に気づいた」という事態を防げると思い、サービスの着想に至りました。


## ユーザー層について

### 対象ユーザー層

キャラクターグッズ収集を愛好しており、好きなコンテンツが多くのグッズを出していたり推しキャラが大勢いたりして予約情報の管理に苦労している人

### 理由

私が上記に当てはまり、グッズの予約情報管理に特化したツールがあれば利用したいと思ったためです。同様のニーズを掘り起こせるのではないかと考えました。
Googleカレンダーやスプレッドシートなど既存のツールによる管理も試みましたが、カレンダーは過去購入したグッズの情報が流れていってしまう点、スプレッドシートはスマートフォンからの記入がしづらい点がネックであると感じました。


## サービスの利用イメージ

### 利用方法

1. 予約開始前のグッズや予約したグッズについて、ユーザーは必要項目を入力してグッズ情報を登録する。
2. ユーザーは登録済のグッズ情報をリスト形式の一覧で確認できる。
3. ユーザーは登録済のグッズ情報を検索できる。
4. グッズの入手後は、所持グッズ情報として引き続き管理できる。

### ユーザーが得られる価値

- 欲しいグッズや予約したグッズを一元管理することで、予約忘れや重複注文を防げる。
- 予約したグッズが手元に届いた後も情報を残しておけるので、所持しているグッズの確認や、後になって売却や譲渡を考えることになった際の記録としても役立つ。


## ユーザーの獲得について

### MVPリリース時

- 活用方法を含めてX(Twitter)などのSNSやnoteなどのプラットフォームで紹介する。
- 友人や知人に使ってもらい、口コミで広めてもらう。

### 本リリース時

- アプリ内のSNS共有機能で露出を増やす。


## サービスの差別化ポイント・推しポイント

既存の持ち物管理アプリとして、1万以上のインストール数がある「**monoca2**」と特定のジャンルに特化した「**JUSCLO**」の2つをインストールして使用感を確認しました。

### monoca2

カスタマイズ性が高く、「モノを管理する」目的において広い領域をカバーできるアプリだと感じます。「欲しいモノ」のカテゴリを使えば予約情報の管理にも利用可能でした。
高度なカスタマイズが可能な分、UIが複雑だったりできることが多すぎたりして戸惑う部分があり、気軽に手に取るには敷居が高いかもしれないと思いました。

### JUSCLO

ファッションアイテムに特化していて、「カラー」「サイズ」「シーズン」などファッション特化ならではの入力項目が用意されており、すぐに使い始めることができました。
「トップス」「シューズ」などのタグは自由に追加・編集が可能でしたが、アイテムの入力項目はファッション関連の内容で固定されています。

また、どちらもAndroid/iOS向けに提供されているネイティブアプリとなります。

### 差別化ポイント

1. WebアプリのためPCでもスマホでも利用可能
2. カスタマイズ不要で手軽
3. キャラクターグッズの予約情報管理に特化
- という方向性で既存アプリとの差別化が可能なのではないかと考えています。
- 特化型のシンプルなアプリとしてリリースし、アップデートによってカスタマイズ性の追加や管理機能の強化を行っていけるのが理想です。


## 機能候補

### MVP

- ユーザー登録
- ログイン
- グッズ情報の登録・編集・削除（名前・予約サイト・予約日・発売予定日・価格・メモ）
- グッズ情報の詳細
- グッズ情報の検索（名前・予約サイトの部分一致検索が可能）
- グッズ情報の一覧表示

### 本リリース

- タグ機能
- お気に入り機能
- ステータス変更機能（予約済→入手済など）
- フィルタ機能
- プッシュ通知による予約開始日や発売日のお知らせ
- UIカラーのカスタマイズ
- 発売予定日までの日数カウント
- 既に同じグッズが登録されている状態で新規登録しようとした際にアラートを出す
- グッズ情報を登録する際にSNSで共有する
- 一覧表示の無限スクロール
- 使い方説明

### 本リリース以降に実装していきたい内容

- 購入金額や予算の計算ができる家計簿機能
- 予約開始日・発売予定日をGoogleカレンダーに連携する


## 機能の実装方針予定

### MVP

- ログイン機能
    - Gem
        - DeviseもしくはSorcery
        
- 検索・フィルタ機能
    - Gem
        - ransack
        
- 一覧表示のページネーション
    - Gem
        - kaminari
    

### 本リリース

- プッシュ通知：PCでもスマホでも通知を受け取れるようにするためWebプッシュ通知を採用したい
    - Gem
        - webpush
    - API
        - Service Worker
        - Push API
    
- UIカラーのカスタマイズ機能
    - Gem
        - rails-settings-cached

- 無限スクロール
    - API
        - Intersection Observer API

### 本リリース以降

- Googleカレンダー連携
    - Gem
        - google-api-ruby-client
        - google-apis-calendar
        - googleauth