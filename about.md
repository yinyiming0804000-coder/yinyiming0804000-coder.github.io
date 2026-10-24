---
layout: default
title: 关于我
permalink: /about.html
---

<section class="wrap section about" aria-labelledby="about-title">
  <div><p class="eyebrow">A little about me</p><h1 id="about-title">关于我</h1><div class="rule"></div></div>
  <div class="about-note">
    <p>你好，我是 {{ site.author | escape }}。我在这里记录网页学习、个人项目与建站实践，希望把每一次尝试整理成可以回顾和分享的文字。</p>
    <ul class="tag-list"><li>网页</li><li>写作</li><li>建站实践</li><li>学习中</li></ul>
    <p class="about-contact"><a href="{{ site.github_url }}">GitHub</a> · <a href="mailto:{{ site.email }}">{{ site.email }}</a></p>
  </div>
</section>
