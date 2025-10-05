<h1>Project Omok</h1>

## 1. 프로젝트 개요

- 







## 3. 파일 구조

'''omok-project/
├── client/                    # Frontend (React)
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── assets/            # 이미지, 사운드 등 정적 파일
│   │   ├── components/        # UI 컴포넌트 (오목판, 채팅창 등)
│   │   ├── pages/             # 페이지 단위 컴포넌트 (홈, 게임룸 등)
│   │   ├── hooks/             # 커스텀 훅
│   │   ├── utils/             # 공용 유틸 함수
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── server/                    # Backend (Node.js + Express or C++)
│   ├── src/
│   │   ├── controllers/       # 라우터 처리 로직
│   │   ├── models/            # DB 모델 (플레이어, 방 등)
│   │   ├── routes/            # API 라우터
│   │   ├── sockets/           # WebSocket 로직
│   │   ├── utils/             # 서버 공용 유틸
│   │   └── index.js
│   ├── package.json
│   └── .env
│
├── shared/                    # 공용 모듈 (타입 정의, 상수, enum 등)
│   ├── types.js
│   └── constants.js
│
├── docs/                      # 기획, 설계 문서
│   ├── architecture.md
│   ├── api-spec.md
│   └── todo.md
│
└── README.md'''
