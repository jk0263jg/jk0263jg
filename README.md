<p align="center">
  <img src="./assets/hero.svg" alt="오재유 | Backend Developer" width="100%">
</p>

<p align="center">
  <a href="mailto:jk0263jg@naver.com"><img src="https://img.shields.io/badge/Email-jk0263jg%40naver.com-03C75A?style=flat-square&logo=naver&logoColor=white" alt="Email"></a>
</p>

## 오재유 | Backend Developer

**Java·Spring Boot와 Python으로 API와 DB를 만들어 온 백엔드 개발자입니다.**

신한대학교 소프트웨어융합학과에 재학 중이며, 글로벌관광경영학과로 입학해 공대로 전과했습니다. 팀 프로젝트에서 서버와 DB를 맡아 위치 정보 앱과 AI 그림일기 앱을 만들었고, AI 모델 대회에도 참가했습니다.

**공공데이터 수집** → **DB·API 구현** → **앱과 연동** → **AI 모델 연결**

## Selected Projects

### 01. DropIt · 의류수거함 위치 찾기 & 의류 나눔

전국 의류수거함 위치를 지도에서 찾고, 후기와 나눔 게시글을 남길 수 있는 서비스입니다. (신한대학교 마이크로스톤 팀 프로젝트, 2025.03 ~ 2025.10)

- **담당 범위:** 백엔드·DB·사용자 관리. 회원·나눔 게시판·후기·즐겨찾기 API와 수거함 조회 API 개발.
- **핵심 구현:** 공공데이터의 전국 의류수거함 위치(약 3.5만 건)를 DB에 적재하고, 지도 화면 범위(bounds) 안의 수거함을 조회하는 API를 구현했습니다.
- **개발 과정:** 공공데이터 API 호출 → 게시판·회원 → JWT 로그인 프로토타입을 단계별로 만든 뒤 하나의 REST API 서버로 합쳤습니다.

`Java` `Spring Boot` `Spring Data JPA` `Spring Security` `MySQL` `PostgreSQL`

[저장소 보기 →](https://github.com/jk0263jg/DropIt)

### 02. 감정 서가 · 감정 기반 AI 그림일기 앱

사용자가 다섯 가지 질문(누가·언제·어디서·무엇을·왜)에 답하면 일기를 쓰고, 감정을 분석하고, 그림일기 이미지까지 만들어 주는 앱입니다. (신한대학교 졸업작품, 2026)

- **담당 범위:** 백엔드, 그림 생성 모델(Illustrious XL) 학습, 문서 작업, 시연 영상 제작.
- **핵심 구현:** FastAPI 백엔드에서 이미지 생성 서비스와 Supabase 테이블 모델을 맡았습니다. 일기 생성 → 감정 분석 → 이미지 생성(ComfyUI + Illustrious XL LoRA) → 저장 순서로 이어지는 파이프라인에 연동했습니다.

`Python` `FastAPI` `Supabase` `PostgreSQL` `ComfyUI` `Kohya_ss` `Illustrious XL`

[팀 저장소 보기 →](https://github.com/kanjunwon/Project_Mood)

### 03. LG Aimers 9기 해커톤 · KBO 투구 제구 성공 확률 예측

투구 직전까지 알 수 있는 정보(볼카운트·주자 상황·선수 특성·과거 이력)만으로 각 투구가 제구에 성공할 확률을 예측하는 모델입니다. 추론 코드와 모델을 통째로 제출하는 코드 제출 대회였습니다. (LG AI연구원 주최·데이콘 주관, Phase 2 온라인 해커톤, 2026.06 ~ 2026.09)

- **과제:** KBO 2019~2024 시즌 약 147만 투구로 학습해 비공개 2025 시즌 약 24.6만 투구를 예측합니다. 평가지표는 Brier Skill Score입니다.
- **핵심 설계:** 과거→미래 방향의 2개 폴드 검증으로, 중요도 1위였지만 2023년에 관계가 뒤집힌 `game_type` 피처를 제거했습니다. 해마다 내려가는 리그 평균 제구 성공률은 로짓 상수로 보정했고, 투구 수가 적은 투수의 과거 성공률은 리그 평균 쪽으로 당겼습니다.
- **제출 환경 대응:** 서버와 Python·라이브러리 버전이 달라 모델이 로드되지 않을 위험을 LightGBM 기본 텍스트 포맷으로 저장해 없앴고, 예외가 나도 제출 파일이 생성되도록 대체 경로를 만들었습니다.
- **결과:** Public Score 793점으로 운영진 기준 점수(549.51점)를 넘었습니다.

`Python` `LightGBM`

[저장소 보기 →](https://github.com/jk0263jg/lg-aimers-kbo-pitch-control)

## Experience & Education

**신한대학교 소프트웨어융합학과 · 재학**
글로벌관광경영학과로 입학한 뒤 소프트웨어융합학과로 전과했습니다. 전공 동아리 마모키에서 활동했습니다.

**신한대학교 마이크로스톤 · 2025.03 ~ 2025.10**
의류수거함 위치 정보 앱에서 백엔드·DB·사용자 관리를 맡았습니다.

**LG Aimers 9기 · 2026.06 ~ 2026.09**
(주)LG경영개발원 AI연구원 Academy Team이 주관한 해커톤에 참가했습니다.

**세명컴퓨터고등학교 스마트콘텐츠과 · 졸업**
웹디자인, 영상편집, 이미지 제작을 배웠습니다.

**자격증**
GTQ 1급 (2018.09) · 웹디자인기능사 (2020.08) · 정보처리기능사 (2020.12) · 컴퓨터활용능력 1급 (2023.07) · 정보처리기사 취득 준비 중

## Tech Stack

**Backend & Data**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**AI**

![LightGBM](https://img.shields.io/badge/LightGBM-555555?style=flat-square)
![Illustrious XL](https://img.shields.io/badge/Illustrious_XL-555555?style=flat-square)
![ComfyUI](https://img.shields.io/badge/ComfyUI-555555?style=flat-square)
![Kohya_ss](https://img.shields.io/badge/Kohya__ss_LoRA-555555?style=flat-square)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

## Contact

- Email: [jk0263jg@naver.com](mailto:jk0263jg@naver.com)
- GitHub: [@jk0263jg](https://github.com/jk0263jg)
