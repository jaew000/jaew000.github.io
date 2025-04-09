---
layout: home
---

# 👋 Welcome to jaew000's Blog!

안녕하세요! 🙌  
프론트엔드부터 웹 개발 기초까지 기록하는 jaew000의 기술 블로그입니다.

HTML, CSS, JavaScript 등 웹 개발 기초부터,  
공부하면서 정리한 내용을 기록하고 공유합니다. 📖

> 이 블로그는 GitHub Pages 로 만들어졌으며, 꾸준히 업데이트됩니다!

---

## 📚 최신 글 목록

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>

---

## 🚀 블로그 바로가기

- [블로그 메인으로](https://jaew000.github.io)

---

## 🗂️ 블로그 카테고리

- HTML & CSS 기초
- JavaScript 기초
- Web 개발 & 꿀팁
- VSCode & 개발 환경 설정
