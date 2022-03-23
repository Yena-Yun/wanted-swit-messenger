
## 🧨 프로젝트 소개

- 주제: SCSS와 Typescript를 활용한 메신저 페이지 구현


## ✈ 배포 링크

## https://luckyzzang-swit-messenger.netlify.app/


## ✨ 구현한 기능

1. **SCSS를 활용**하여 **채팅창 페이지의 UI** 구현
2. 채팅창의 **댓글 작성 기능** 구현
3.  **SCSS에서 props를 전달하는 공통 컴포넌트**를 작성하여, **입력 시 활성화되는 전송버튼** 구현
4.  첫 로딩 때 **data.ts에 있는 기존 데이터를 렌더링**
5. **메시지 작성 날짜를 yyyy-mm-dd hh:MM:ss 형태로 출력**하는 **util 함수(formatDate)** 생성
 
⚜ 그 외 구현된 기능
* 리덕스, 모달, 로그인 기능

## 4. 기술 스택
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![scss](https://img.shields.io/badge/scss-DB7093?style=for-the-badge&logo=styled-components&logoColor=white) 


## 5. 디렉토리 구조

```bash
.
├── App.tsx
├── assets      # icons, images
├── components
│   ├── Login
│   ├── messageCard
│   └── messageModal
├── hooks
│   ├── useBlockScroll
│   ├── useBottomScroll
│   └── useControlModal  
├── pages
│   └── Main
├── store     # redux 구성 파일
│   ├── actions   # redux action
│   ├── data.ts   # 대화목록 data
│   └── reducers
│       ├── auth.ts     # 사용자 reducer
│       ├── message.ts  # 대화 목록 reducer
│       └── utils       # reducer 관련 utils 함수
├── types     # typescript type 선언 파일
└── utils     # 자주 사용하는 함수
```


## 6. 설치 및 실행 방법
클라이언트 실행
    ```bash
    npm run start
    ```


## 7. 커밋 컨벤션

깃모지를 사용하여 이모티콘만 보고 커밋의 목적이나 의도를 쉽게 식별할 수 있도록 하였습니다.

| 깃모지 | 사용 예시 |
| --- | --- |
| :sparkles: | 기능 구현 |
| :lipstick: | CSS 스타일링 |
| :wrench: | utils 함수나 types 추가 |
| :fire: | 파일 삭제 |
| :wastebasket: | 코드 삭제 |
| 🚚 | 디렉토리 또는 파일 이동 |
| :package: | 패키지 설치 |
| ♻️ | 리팩토링 |
| 📝 | Readme 수정 |
| 🐛 | 버그 수정 |
