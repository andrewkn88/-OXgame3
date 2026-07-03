# 실시간 OX 퀴즈 웹앱

## 프로젝트 소개

강사와 학생이 동시에 참여하는 실시간 OX 퀴즈 웹앱입니다.

## 주요 기능

-   강사 화면(`#admin`)
-   학생 화면(`/`)
-   O/X 문제 진행
-   시트(엑셀/구글시트) 붙여넣기
-   AI 문제 생성(예정)
-   모바일 최적화
-   Firebase Realtime Database 연동 가능

## 폴더 구조

``` text
/
├── index.html
├── README.md
└── assets/ (선택)
```

## 실행 방법

### 로컬

`index.html`을 브라우저에서 실행합니다.

### GitHub + Vercel

1.  GitHub 저장소 생성
2.  `index.html`과 `README.md` 업로드
3.  Vercel에서 Import Project
4.  Deploy

## Firebase 연동(예정)

1.  Firebase 프로젝트 생성
2.  Realtime Database 활성화
3.  `firebaseConfig` 입력
4.  배포

## 문제 입력 형식

탭으로 구분하여 붙여넣습니다.

``` text
지구는 둥글다 O
서울은 일본의 수도이다    X
```

## 향후 개발 계획

-   실시간 랭킹
-   타이머
-   해설 표시
-   틀린 문제 다시 풀기
-   AI 자동 문제 생성
-   강사 통계 화면

## 라이선스

MIT License
