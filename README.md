## SKPACK manual
정적 사이트 생성기인 hugo를 이용해 제작 한 skpack admin 페이지의 웹 메뉴얼

## 사전 준비
node v18 이상

https://nodejs.org/en

go v1.20 이상

https://go.dev/

hugo v0.115

https://gohugo.io/installation/windows/

## hugo 템플릿
Docsy

https://www.docsy.dev/

## hugo 개발 서버
패키지 설치
```
npm install --legacy-peer-deps
```

hugo.toml의 baseURL를 `/`으로 수정 후 아래 명령어 실행
```
hugo server
```
hugo 개발 서버 디폴트 포트인 localhost:1313으로 접속 확인 

## 빌드
아래 명령을 이용해 빌드하면 `public` 폴더 밑에 빌드 됨
```
hugo
```

## 배포
public 밑의 파일을 `skpack-backend-deploy`에서 마운트 한 경로인 다음 경로로 이동 `/app/media/manual`
