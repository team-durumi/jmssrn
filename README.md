# jmssrn.org | 일본군'위안부' 연구회 홈페이지

## Assets
- https://jmssrn.org/
- https://jmssrn.org/admin
- https://github.com/team-durumi/jmssrn

## Dev
```
npm i
go mod init github/team-durumi/tailwind-aa-theme
go mod download
hugo mod get -u
hugo server
```
- 오랜만에 개발 환경 확인할 때
```
hugo mod clean
go mod tidy
```

## Netlify build command
```
netlify build command:
hugo mod get -u ./... && hugo --gc --minify
```

