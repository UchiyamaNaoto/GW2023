〇アプリの概要

読書日記
日記アプリに、読書状態を持った本が必ずタグ付けされるようなものをイメージして作りました

〇実装機能（β版）

・BookClass(Id(PK, AutoIncrement), Title(NotNull), Writer, Publisher, Genre, ISBN, Status, Comment) - SQLite
・DiaryClass(DateTime(Index, NotNull), BookId(Index, NotNull), BookTitle, Title, MainText) - SQLite
Book登録機能、Diary登録機能
CalendarからのDiary参照、Diary登録
BookShelfからのBook参照(Statusで色分け)、Diary参照(本ごとに絞り込み)、Book登録、Diary登録
SettingPageの作成 - Properties.Settings.settings
(StartPageのBook一覧…… 少なくともButtonは除去予定)

○残作業

Calendar 日付で日記を絞り込む
DiaryCollection DateTimeが一致する日記を返す
（前頁から要素を引き継いだページ遷移 バグる）
（APIをつないで保存するBookデータの精度を上げる モノにはなるので時間があれば）
（StartPageのBook一覧　除去するか、体裁を整える）
（BookShelfのヒントボタンを作るか消す）
（Setting.settingsが初期値から動かない謎を解く）

○その他



▼参考にしているサイト等（Unity）

　たくさんあります