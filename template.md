月曜日に先週一週間のMySQL関連の更新を再確認するのにご活用ください。

# Release note

(https://dev.mysql.com/doc/relnotes/mysql/8.0/en/)

- Nothing

# Bugs

`serverity >= S5(Performance)`でupdatedでdesc sort、結果の今週分を見る

[条件を適用した検索結果](https://bugs.mysql.com/search.php?cmd=display&status=All&severity=-5&os=5&bug_age=0&order_by=mtime&direction=ASC&limit=30&mine=0&reorder_by=mtime)

## Bug #???

[title](url)

- aa

# Organization blogs

- MySQL server blog: https://mysqlserverteam.com/
  - Nothing

- MySQL High Availability blog: https://mysqlhighavailability.com/
  - Nothing

- Percona blog (MySQL): https://www.percona.com/blog/
  - [Using linux-fincore to Check Linux Page Cache Usage](https://www.percona.com/blog/2019/08/29/using-linux-fincore-to-check-linux-page-cache-usage/)
    - MySQLと直接関係ないがtagもMySQLがついているので紹介
    - [linux-fincore](https://github.com/yazgoo/linux-ftools) と記事内で書かれているツール(linux-ftools)の紹介
    - ファイルを指定して、ページキャッシュに乗っているか、どの程度のページを確保しているかを確認することができる

- MySQL道普請: https://gihyo.jp/dev/serial/01/mysql-road-construction-news
  - [第104回　MySQLのROLE［その2］](https://gihyo.jp/dev/serial/01/mysql-road-construction-news/0104)
    - 第102回の概要・作成方法に続くrole機能の紹介
    - `mandatory_roles`, `active_all_roles_on_login`について説明

- SmartStyle TECH BLOG (MySQL): https://www.s-style.co.jp/blog/category/tech/mysql/ & https://www.s-style.co.jp/blog/category/tech/percona/
  - [MySQL8.0.17 新機能紹介：Redo ログのアーカイブについて](https://www.s-style.co.jp/blog/2019/08/5060/)
    - redo_logのアーカイビング機能を設定するのに必要なinnodb_redo_log_archive_dirに関する設定方法と注意点が詳しい
    - この機能の導入経緯、ユースケースについても紹介され、現状のbackupツールのサポート状況についても説明されている
- Severalnines Database Blog: https://severalnines.com/database-blog
  - [Comparing Failover Times for Amazon Aurora, Amazon RDS, and ClusterControl](https://severalnines.com/database-blog/comparing-failover-times-amazon-aurora-amazon-rds-and-clustercontrol)
    - AWSのAurora, Amazon RDS, severalnines社のツールらしきClusterControlでMultiAZで構成されたMySQL replica-setでFailoverにかかる時間の比較
    - 結論としては
      - Aurora: 7sec
      - ClusterControl: 11sec
      - RDS: 27sec
      となっている。
    - 実際AWSの2サービスでは突然の障害ではなく、GUIからの操作でFailoverを意図して行っているので、もしかしたらなにかFailoverが早くなるような操作が事前に走っていたりしないかな？なんて思ったりした。

- Yakst MySQL-tag: https://yakst.com/ja/tags/mysql
  - Nothing



# Personal blogs

- [title](url)
- aa

- [Join the Code ONE MySQL Track at Oracle Open World in San Francisco](https://lefred.be/content/join-the-code-one-mysql-track-at-oracle-open-world-in-san-francisco/)
  - OOW中?に開催するMySQL Receptionの案内
  - これ個人のブログで告知するんだ（個人で開催してるのか？）と思った
  - OOWのMySQL trackも紹介されている
    - https://events.rainfocus.com/widget/oracle/oow19/catalogcodeone19?search.codeonetracks=15560568230440116cnc
- [MySQL Technology Cafe #5 に参加してきた](http://mita2db.blogspot.com/2019/08/mysql-technology-cafe-5.html)
  - MySQL Technology Cafe #5への振り返り記事
- [HammerDBをCLIで使うなど（２）：MySQLにTPC-Cを実行してみる](http://atsuizo.hatenadiary.jp/entry/2019/08/27/090000)
  - HammerDBというDBMSベンチマークソフトでMySQLにベンチマークを実行するまでの設定を解説
  - そもそもHammerDBについての説明もされているので、まずは[HammerDBをCLIで使うなど（１）：環境構築](http://atsuizo.hatenadiary.jp/entry/2019/08/26/090000)を読んでみると良さそう
  - この他HammerDBで対応されているDBMSへのベンチマーク方法もこのシリーズで説明されている


- personal
  - https://opensourcedba.wordpress.com/
  - https://lefred.be/
  - http://dimitrik.free.fr/blog/index.html
  - http://oysteing.blogspot.com/
  - https://elephantdolphin.blogspot.com/
  - https://mysql.wisborg.dk/
  - http://dasini.net/blog/en/
  - https://www.fromdual.com/blog/41
  - http://nippondanji.blogspot.com/
  - http://blog.kimuradb.com/
  - https://yoku0825.blogspot.com/
  - http://sakaik.hateblo.jp/
  - https://tmtms.hatenablog.com/
  - http://mita2db.blogspot.com/
  - https://www.slideshare.net/takanorisejima/
  - http://kenken0807.hatenablog.com/
  - https://ichirin2501.hatenablog.com/
  - http://atsuizo.hatenadiary.jp/
  - https://blog.kamipo.net/
  - http://hiroi10.hatenablog.com/
  - https://qiita.com/hmatsu47
  - http://next4us-ti.hatenablog.com/
  - https://tombo2.hatenablog.com/



-----

このブログ記事はGitHub上で管理されています[MySQL-weekly repository](https://github.com/tom--bo/MySQL-weekly)。Issue, pull-request歓迎です。(完全に同期できているわけではありません)
