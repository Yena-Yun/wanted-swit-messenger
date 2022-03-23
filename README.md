
## 1. 프로젝트 소개

- 주제 : 메신저
- 기간 : 22.02.10 ~ 22.02.12



## 2. 배포 링크

https://luckyzzang-swit-messenger.netlify.app/


## 3. 구현 기능

⚜ 윤예나
* 채팅창 페이지 UI
* 채팅창 댓글 작성 기능
* data.ts에 있는 기존 데이터 렌더링
* 입력 시 전송버튼 활성화 (scss의 props 작업)
* 날짜 util 함수 (yyyy-mm-dd hh:MM:ss 형태로 출력)

⚜ 이지용
* 리덕스 기능

⚜ 안병진
* 모달 기능
    
⚜ 박민주
* 로그인 기능
  

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
