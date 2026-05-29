# 우시아 (Wooshia) — Backend & Blockchain Developer

> 시스템의 원리를 끝까지 파고드는 개발자.  
> 로우레벨 구조 이해를 바탕으로 블록체인 프로토콜과 백엔드 인프라를 탐구합니다.

---

## 🧑‍💻 About Me

동국대학교 컴퓨터공학과 재학 중이며, 동대신문사 기자로도 활동하고 있습니다.  
단순히 작동하는 코드가 아니라 **왜 작동하는가**를 이해하는 것을 목표로 삼습니다.

Linux 파일시스템과 x86-64 어셈블리 레벨에서 출발해, 현재는 **Ethereum MEV 봇**, **DeFi 프로토콜 분석**, **비동기 백엔드 시스템**을 직접 설계·구현하며 공부하고 있습니다.

---

## 🔧 Skills

### Blockchain / Web3
- **Solidity** — 플래시 론 콜백 패턴, 스마트컨트랙트 설계 (`ArbBot.sol`)
- **Ethers.js v6 / Node.js** — 멤풀 모니터링, 온체인 트랜잭션 자동화
- **MEV** — Flashbots 번들 제출, Searcher–Builder–Validator 구조 이해
- **DeFi 프로토콜** — Uniswap V2/V3 AMM(x·y=k, tick/liquidity), 플래시 론 원자성
- **개발환경** — Hardhat 로컬 포크, Sepolia 테스트넷, Rabby Wallet

### Backend
- **FastAPI + SQLAlchemy(async) + PostgreSQL** — CRUD API 설계 및 구현
- **비동기 디버깅** — `asyncio.gather` + 공유 세션 충돌(`IllegalStateChangeError`) 해결 경험
- **DB 커넥션 풀링** — HikariCP 공식 이해, 커넥션·세션 개념 구분
- **Python** — 주력 언어, FastAPI·pygame 등 다양한 용도로 활용

### Systems
- **Linux** — ext 파일시스템(superblock, inode, data block), 커널 개념
- **Assembly** — nasm, ELF64, x86-64 레지스터 계층(rax/eax/ax/ah/al)
- **Java** — OOP(JVM, 바이트코드, 상속, 다형성)

---

## 🚀 Projects

### MEV Arbitrage Bot
> Ethereum 메인넷/Sepolia 기반 차익거래 봇

- Uniswap V2/V3 가격 차이를 탐지하는 멤풀 모니터링 구조 설계
- Solidity `ArbBot.sol` — 플래시 론으로 무담보 차익거래 구현
- Flashbots 번들 제출을 통한 프론트런·샌드위치 공격 회피 구조 학습
- **Stack:** Node.js, ethers.js v6, Solidity, Hardhat, Flashbots

### Async Backend API
> FastAPI + PostgreSQL 기반 비동기 REST API

- SQLAlchemy async 세션 관리 및 커넥션 풀 설계
- 동시 요청 처리 중 트랜잭션 상태 충돌 버그 직접 디버깅·해결
- **Stack:** Python, FastAPI, SQLAlchemy(async), asyncpg, PostgreSQL

### Particle Heart Animation
> pygame 기반 창작 시각화 프로젝트

- 파티클 시스템, 공전 보석, 줌 기능, 별 배경을 결합한 인터랙티브 애니메이션
- **Stack:** Python, pygame

---

## 📰 Other Experience

**동대신문사 기자** — 동국대학교 교내 신문  
- 의대 정원 정책 취재 (교수진 직접 인터뷰·섭외)
- 지방 거주 대학생 부모 대상 기획 기사 작성
- 기술 개념을 비전공자에게 명확히 전달하는 커뮤니케이션 훈련

---

## 🎓 Education

**동국대학교** 컴퓨터공학과 (재학 중)

---

## 📫 Contact

- GitHub: [github.com/resistance9](https://github.com/resistance9)
- Email: lwh0095@gmail.com
