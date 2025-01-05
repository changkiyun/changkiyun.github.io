---
title: "Gatsby 테마를 적용한 Github 블로그 만들기 (3)_Github Pages 로 배포하기"
description: "Github Page 로 배포하기"
date: 2025-01-07
update: 2025-01-07
tags:
  - Gatsby
  - Node.js
series: "Gatsby 테마를 적용한 Github 블로그 만들기"
---

## Github 레포지토리 생성

giscus 설정까지 완료했다면 드디어 블로그를 배포해볼 차례입니다.

```
[사용자이름].github.io
```
깃허브에서 위의 이름 형식으로 레포지토리를 생성해줍니다. 

```
npm run deploy-gh
```
이후 터미널로 돌아와 위의 명령어를 입력하고 빌드가 완료될 때까지 잠시 기다렸다가

```
https://[사용자이름].github.io

```
브라우저에서 위 형식의 경로로 접속하면 Gatby 테마로 만든 블로그가 배포되는 것을 확인할 수 있습니다.

우여곡절도 많았지만 어쨌든 이런 과정을 통해 Gatsby 테마를 사용한 Github 블로그를 배포할 수 있었습니다. 고생해서 만든 만큼 열심히 운영해보도록 하겠습니다. 

다음 포스팅은 블로그 글 작성방법, 마크다운 문법 등을 소개해보도록 하겠습니다.