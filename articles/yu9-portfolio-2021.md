---
title: "Vue.jsとmicroCMSで更新しやすいポートフォリオを作成"
emoji: "😎"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["vue", "tailwindcss", "microcms"]
published: false
---
Vue.jsとmicrocmsでポートフォリオを作りました。その際のことをまとめていきます。
# 目的
『更新しやすいポートフォリオを作る』
いままでポートフォリオを作成しましたがいずれも新しい作品を追加するのが手間でした。
htmlを編集する場合は、作品などが増えるほど編集しづらくなります。またデータベースで登録する場合、管理画面の実装が必要になります。
最終的にサイト更新をしなくなりポートフォリオとしての機能をなさないということが起きていました。
# 言語やインフラの選定
## サーバー
ポートフォリオの公開にはGithubPagesとレンタルサーバーの2つで公開します。GithubPagesはサンドボックスで、レンタルサーバーは正式版ということにしました。
## 言語
- Vue
もともとVueの学習をするためにポートフォリオを作成しなおしました。なのでvueを使います。
## CMS
- microCMS
ヘッドレスCMSの一つです。コンテンツの保存と管理はmicroCMSで行い、フロントエンドの開発に重点をおきます。


