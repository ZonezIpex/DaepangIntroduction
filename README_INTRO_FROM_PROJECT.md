<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&size=34&pause=1200&color=111111&center=true&vCenter=true&width=1000&lines=Daepang+%28%EB%8C%80%ED%8C%A1%29;Study+Notes+%2B+Quiz+%2B+Roadmap+in+One+Place" alt="Daepang Typing" />
</p>

<p align="center">
  <a href="https://github.com/ZonezIpex/Daepang-front"><img src="https://img.shields.io/badge/Frontend-Repo-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://github.com/ZonezIpex/Daepang-back"><img src="https://img.shields.io/badge/Backend-Repo-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p align="center">
  <img src="대팡 프로젝트 포스터.png" alt="Daepang Poster" width="720" />
</p>

<br/>

## 📚 목차
1. [프로젝트 소개](#1-프로젝트-소개)  
2. [왜 만들었나](#2-왜-만들었나)  
3. [핵심 기능](#3-핵심-기능)  
4. [전체 구조](#4-전체-구조)  
5. [기술 스택](#5-기술-스택)  
6. [팀](#6-팀)  
7. [소개 자료/시연](#7-소개-자료시연)

<br/>

## <a id="1-프로젝트-소개"></a> 1. 프로젝트 소개
대팡은 공부하면서 생기는 자료(필기/요약/문제)를 한 곳에 모아 정리하고,  
자료를 기반으로 퀴즈를 만들어 풀면서 복습까지 이어지도록 구성한 학습 통합 프로젝트입니다.  
공부 흐름이 끊기지 않게 **정리 → 확인(퀴즈) → 복습**을 한 번에 처리하는 흐름을 목표로 했습니다.

<br/>

## <a id="2-왜-만들었나"></a> 2. 왜 만들었나
- 자료가 쌓일수록 “어디에 뭘 정리했는지”부터 헷갈리고, 다시 찾는 시간이 계속 늘어났습니다.
- 노트/요약/문제/복습이 분리돼 있어 공부 흐름이 자주 끊겼습니다.
- 그래서 학습을 “진행 가능한 상태”로 만들어주는 통합 구조로 묶어보자는 방향으로 시작했습니다.

<br/>

## <a id="3-핵심-기능"></a> 3. 핵심 기능
### 3.1 자료 정리/관리
- 학습 자료를 한 곳에 모아 정리하고, 필요한 자료를 빠르게 다시 확인할 수 있게 구성했습니다.

### 3.2 퀴즈 생성/풀이(복습 루프)
- 자료를 바탕으로 퀴즈를 만들고 풀이/결과를 통해 복습 루프를 만들었습니다.

### 3.3 로드맵
- 목표(시험/자격증/취업 준비)에 맞춰 단계를 나누고, 학습 진행을 따라갈 수 있게 구성했습니다.

### 3.4 공유/커뮤니티(확장 방향)
- 자료를 공유하거나, 다른 사람 자료를 참고할 수 있는 흐름으로 확장 가능한 구조를 염두에 뒀습니다.

<br/>

## <a id="4-전체-구조"></a> 4. 전체 구조
<pre>
[ Frontend (React) ]
        ↓
[ REST API ]
        ↓
[ Backend (Node/Express) ]
        ↓
[ MySQL ]
</pre>

- 화면(UI)과 사용자 흐름은 프론트에서 담당합니다.
- 인증/권한 및 데이터 처리/AI 요청 등 핵심 로직은 백엔드에서 처리합니다.

<br/>

## <a id="5-기술-스택"></a> 5. 기술 스택
- **Frontend**: React(CRA), TypeScript, React Router, Markdown Editor(MDEditor/Preview), diff-match-patch  
- **Backend**: Node.js, Express, JWT(jsonwebtoken), bcryptjs, mysql2, OpenAI SDK  
- **Database**: MySQL  

<br/>

## <a id="6-팀"></a> 6. 팀
- 신민수: 프로젝트 총괄, 백엔드 개발, 설계/발표
- 김민식: 백엔드 개발, DB 설계, 유지보수
- 이준환: 프론트엔드 개발, 발표자료 작업/디자인 수정

<br/>

## <a id="7-소개-자료시연"></a> 7. 소개 자료/시연
- 소개 자료(PDF): `대팡 프로젝트.pdf`
- 포스터: `대팡 프로젝트 포스터.png`
- 시연 영상: `대팡 프로젝트 동영상.mp4`

<br/>

### Repository
- Frontend: https://github.com/ZonezIpex/Daepang-front  
- Backend: https://github.com/ZonezIpex/Daepang-back  
