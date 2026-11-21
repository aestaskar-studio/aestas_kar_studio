---
layout: default
title: Profile
permalink: /about/
---

<section class="profile-card">
  <div class="profile-avatar" aria-hidden="true">a</div>
  <h1 class="profile-name">{{ site.author.name }}</h1>
  <p class="profile-bio">
    <!-- ここに一言自己紹介を書いてください -->
    {{ site.description }}
  </p>
  <div class="profile-links">
    <a class="profile-btn" href="https://x.com/{{ site.author.x }}" target="_blank" rel="noopener">X @{{ site.author.x }}</a>
    <a class="profile-btn outline" href="https://github.com/{{ site.author.github }}" target="_blank" rel="noopener">GitHub</a>
  </div>
</section>

<!-- 下の項目は自由に書き換え・削除してください -->

## About me

ここに自己紹介を書きます（例：やっていること、好きなもの、このブログで書きたいこと）。

## Skills

- （例：よく使う言語やツール）
- （例：最近触っている技術）

## Contact

ご連絡は [X @{{ site.author.x }}](https://x.com/{{ site.author.x }}) までどうぞ。
