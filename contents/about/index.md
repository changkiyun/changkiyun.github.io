---
title: "This is about page ✋"
---
## 한국어 가이드

안녕하세요. 이 곳은 블로그를 소개하기 위한 공간입니다. 블로그 또는 자신에 대한 소개부터 이력서, 포트폴리오 등 다양한 정보를 이곳에서 방문자들에게 보여줄 수 있습니다.

### 작성 가이드

이 페이지를 편집하려면, `/contents/about/index.md` 파일을 수정하면 됩니다. 다른 포스팅을 작성하는 것과 동일한 방식으로 작성할 수 있습니다. 이 파일의 경로는 변경할 수 없습니다.

About 페이지의 마크다운 문서는 오직 `title` 이라는 하나의 frontmatter 만 가지고 있습니다. `title` frontmatter 는 About 페이지 상단 제목으로 표시됩니다.

### 비활성화

```json
module.exports = {

  // ...

  useAbout: false, // 👈

  // ...

}
```

`blog-config.js` 파일의 `useAbout` 값을 `false` 로 설정하여 About 페이지를 비활성화 할 수 있습니다. 비활성화 된다면, 블로그 상단에 존재하는 탭이 숨겨지고, `/about` 경로로 이 페이지에 접속할 수도 없게 됩니다.
