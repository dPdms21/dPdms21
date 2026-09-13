![header](https://capsule-render.vercel.app/api?type=waving&color=A9B5DF&height=150&section=header&text=Yeeun%20Park%20%7C%20Backend%20Developer&fontSize=28&fontAlignY=30&animation=twinkling)

# 👋 Hi, I'm Yeeun Park

### 문제를 끝까지 파고들어 해결하며 서비스의 완성도를 높이는 백엔드 개발자 박예은입니다.

Java와 Spring Boot를 중심으로 백엔드 개발을 공부하고 있습니다.  
기능 구현에 그치지 않고 **데이터 정합성, 동시성, 성능, 서비스 운영**까지 고민합니다.

로그와 테스트를 기반으로 문제의 원인을 좁히고,  
기술을 선택할 때는 **어떻게 구현할지뿐 아니라 왜 필요한지**를 함께 고민합니다.

---

## 🛠 Tech Stack

### Backend

<p>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
</p>

### Database & Platform

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white"/>
</p>

### Infra, Monitoring & Test

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white"/>
</p>

### Other

<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
</p>

---

## 🚀 Featured Projects

### 🛒 [Gudit](https://github.com/prgrms-be-devcourse/NBE11-13-2-Team03)
**한정 수량 굿즈의 안정적인 선착순 구매와 결제를 위한 타임세일 서비스**

`Java` `Spring Boot` `PostgreSQL` `Redis` `Toss Payments` `k6`

**담당**
- Purchase · Payment 도메인
- 결제 승인·취소 흐름
- 결제 동시성 및 데이터 정합성 테스트

**주요 경험**
- Redis와 Lua Script를 활용한 재고 차감 및 복구 처리
- Purchase · Payment 상태 전이에 비관적 락을 적용해 동시 요청 제어
- 외부 결제 승인 이후 내부 DB 처리 실패 시 Toss 자동 보상 취소 흐름 구현
- 동일 결제 동시 요청을 k6로 재현해 **1건 성공 / 49건 정상 거절 / 비정상 응답 0건**으로 정합성 검증

🏆 **Programmers Devcourse 2차 프로젝트 최우수팀**

---

### 🌿 [Chaerok](https://github.com/team-chaerok/chaerok-be)
**충남 지역의 여행 경험을 필름처럼 기록하는 관광 서비스**

`Java` `Spring Boot` `PostgreSQL` `OAuth2` `JWT` `TourAPI` `Kakao Local API` `Prometheus` `Grafana`

**담당**
- 사용자 · 인증 · 지역 정보 백엔드 기능
- 관광 장소 조회 · 검색 및 추천 코스 기능
- 외부 관광 데이터 API 연동
- 백엔드 배포 · 모니터링 환경 구성 및 운영 대응

**주요 경험**
- Kakao · Google · Apple OAuth 기반 로그인과 JWT 인증 흐름 구현
- TourAPI와 Kakao Local API를 활용한 관광 장소 조회·검색 기능 개발
- TOURISM · FOOD · CAFE_DESSERT 세 카테고리를 보장하는 추천 코스 검증 로직 구현
- Render · Supabase 환경에서 백엔드를 배포하고 Spring Boot Actuator · Prometheus · Grafana 기반 서버 메트릭 모니터링 환경 구성
- Render 환경의 JVM 메모리 제한과 외부 API Timeout 등 운영 이슈를 조정하며 안정성 개선
- 현재 Google Play · App Store 심사 진행 중

**📱 2026 관광데이터 활용 공모전 웹·앱 개발 부문 참가**

---

### 🎵 [S:ote](https://github.com/dPdms21/sote-be)
**AI 감정 분석 기반 음악·챌린지 추천 일기 서비스**

`Java` `Spring Boot` `PostgreSQL` `FastAPI` `JWT` `Firebase`

**담당**
- 인증 · 인가 및 사용자별 데이터 접근 제어
- AI 감정 분석 · 음악 추천 기능
- 챌린지 · LP 보상 흐름
- STT 음성 입력 · 사용자 통계 기능
- FastAPI AI 서버 연동 및 서비스 흐름 안정화

**주요 경험**
- AI 서버 Cold Start로 첫 분석이 실패하는 문제를 확인하고, Wake 요청과 분석 요청·결과 저장 흐름 분리로 비동기 사용자 흐름 개선
- 감정 분석 결과를 챌린지 추천 → 완료 → 음악 LP 보상으로 연결하는 상태 흐름 구현
- JWT 기반 인증·인가를 적용해 사용자별 분석 · 챌린지 · 음악 추천 데이터 접근 제어
- STT 기반 음성 입력과 감정 · 활동 통계 조회 기능 구현
- 서비스 배포 및 교내 전시 진행

🏆 **2025 캡스톤 경진대회 아리상**

---

## 📚 Research

### [Semantic-aligned multimodal human activity recognition using visual and audio data](https://doi.org/10.11591/ijece.v16i4.pp2087-2095)

- Visual · Audio 기반 Multimodal Human Activity Recognition 연구 주도
- HMDB51 · ESC-50 데이터를 전처리하고 ResNet-18 기반 Image · Audio 모델 학습 및 실험 수행
- Image · Audio 예측 logits를 결합하는 **Score-level Weighted Late Fusion 구조를 설계하고 fusion weight를 조정하며 성능 비교**
- 단일 모달 모델 대비 Fusion Model의 성능 향상을 검증해 **Accuracy 92.67% / Macro-F1 92.49%** 달성
- *International Journal of Electrical and Computer Engineering (IJECE)* 게재

---

## 🏆 Awards & Activities

### Awards
- **Programmers Devcourse 2차 프로젝트 최우수팀** — Gudit
- **2025 캡스톤 경진대회 아리상** — S:ote

### Activities
- **Programmers Devcourse Backend 11기**
- **2026 관광데이터 활용 공모전 웹·앱 개발 부문 참가** — Chaerok
- **9oormthonUNIV 4기 SEASONTHON 참가** — essaily

---

## 🔎 Interests

- Backend performance & load testing
- Concurrency & data consistency
- Monitoring & observability
- Cloud infrastructure

---

## 📌 Development Approach

**문제를 먼저 정의합니다**  
기술을 먼저 적용하기보다 해결해야 할 문제와 요구사항을 먼저 확인합니다.

**근거를 바탕으로 판단합니다**  
로그, 메트릭, 테스트 결과를 활용해 원인을 좁히고 기술적 선택의 근거를 만듭니다.

**트레이드오프를 고려합니다**  
성능뿐 아니라 데이터 정합성, 구현 복잡도, 운영 비용과 팀의 상황까지 고려합니다.

**결과를 검증합니다**  
개선했다고 판단하는 데서 끝내지 않고 가능한 경우 동일한 조건의 테스트와 수치로 결과를 확인합니다.

---

## 📫 Contact

- Email: `studye20@gmail.com`
- ORCID: [0009-0001-6368-6746](https://orcid.org/0009-0001-6368-6746)

![footer](https://capsule-render.vercel.app/api?type=waving&color=A9B5DF&height=120&section=footer&animation=twinkling)