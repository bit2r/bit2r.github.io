# 비트알 웹사이트

비트알 웹사이트 레파지토리

## 웹사이트 정보

### 도메인

<https://r2bit.com>

<https://bit2r.github.io>

### 호스팅

Github pages

### 프레임워크

Rstudio Distill

### 테마

커스텀

## 사이트 콘텐츠 수정 방법

1. Rstudio로 bit2r-website.Rproj 파일을 오픈한다.
2. 콘텐츠를 추가, 수정, 삭제한 후 Rstudio의 메뉴에서 Build - Install and Restart 또는 Build - Build All을 선택해서 웹사이트를 빌드한다.
3. 생성된 콘텐츠를 커밋하고 Github에 push한다.

## 서울R미트업 Seoul R meetup

Seoul R meetup 콘텐츠는 Rmarkdown으로 제작했으며 빌드는 quarto로 할 수 있음

### 테마

cosmo + custom.css

### 빌드 방법

이 레파지토리를 클론 받은 후에 __seoul-r-src 로 이동

quarto로 빌드

```sh
quarto render
```

빌드 후에 생성된 콘텐츠는 ./docs/seoul-R 에 저장됨
