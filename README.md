# hugo project scaffold

Dev
```
go mod init github/team-durumi/tailwind-aa-theme
go mod download
```

Netlify build
```
netlify build command:
hugo mod tidy && hugo --gc --minify
```


## Site building

1. 우선 홈페이지 범위부터 말씀드리면, 연구회 소개와 공지, 학술행사 시의 자료 업로드 정도의 기능이 전부일 것 같습니다. 필요하다고 생각되는 메뉴들을 대강 말씀드리면,

about | 학회소개: 간략한 소개 / 연혁 / 회장 인사말 / 학회임원 / 회칙
posts | 공지사항: 행사안내 / 보도자료
articles | 학회활동: 학술행사 / 발간물 / 사회참여
회원가입 | 구글 폼 링크
