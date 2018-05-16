---
layout: post
title:  rbenv환경에서 Jekyll 블로그 생성하고 GitHub Pages에 배포하기
date:   2016-12-29 18:34:10 +0700
categories: [jekyll]
---

이 포스팅에서는 `macOS`환경에서 `rbnv`를 사용해 `Jekyll`블로그를 생성하고,<br>
이를 `GitHub Pages`에 배포하는 방법을 다룬다.
<hr>

#### Jekyll?

`Jekyll`은 일반적으로 블로그를 만들기 위해 사용하는 정적 사이트 생성기이다.<br>
데이터베이스를 사용하지 않고 `git`과 같은 버전관리 시스템을 사용해 포스트들을 관리하며, 정적 웹사이트이기 때문에 단순 파일 서빙만으로 블로그를 만들 수 있다.

정적 웹 사이트라는 특징덕에 `GitHub`에서는 `Jekyll`블로그를 서빙하기 위한 시스템을 제공하며 무료로 사용가능하다.
