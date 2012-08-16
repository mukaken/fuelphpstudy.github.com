---
layout: page
title: Hello FuelPHP Study!
tagline: Supporting tagline
---
{% include JB/setup %}

ようこそ。ここは『FuelPHP勉強会』のまとめページです。

## このサイトについて

現在このサイトは鋭意準備中です。

詳しくは [fuelphpstudy リポジトリの Wiki](https://github.com/fuelphpstudy/fuelphpstudy.github.com/wiki) をご確認ください。このページでもお知らせを更新いたします。

## 現在開催予定の勉強会

- [FuelPHP 勉強会 東京 vol.2](http://atnd.org/events/31017 "FuelPHP 勉強会 東京 vol.2 : ATND")

## 過去の開催一覧

- [comming soon...]()

## 記事一覧

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> - <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

