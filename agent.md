# Agent Working Memory

Last updated: 2026-03-02 (Asia/Seoul)

## Purpose
이 문서는 해외(미국) 타겟 인스타/틱톡/유튜브 숏폼 사업 실행 시, 이전 대화 맥락을 유지하고 세션마다 누적 기록을 남기기 위한 운영 메모다.

## Core Goal
- 1차 목표: 미국 타겟 숏폼 계정 성장
- 장기 목표: 월 3,000만 원 이상 수익 가능한 콘텐츠 자산/포트폴리오 구축
- 운영 방향: 취미가 아닌 3개월 올인 프로젝트 기반의 시스템 운영

## Confirmed Direction from Prior Chat
- 타겟: 미국 중심 영어권
- 포맷: 감성/시네마틱 + 음악/가사 의미 전달
- 브랜드 방향: 음악 채널보다 "감정 채널" 포지셔닝
- 계정 운영: 새 계정 생성(이메일 기반), 2FA 필수, 영어 일관성 유지
- 계정 카테고리(인스타): `Musician` 우선, 필요 시 `Artist`
- 한줄 소개 선호: `Daily song meanings in 15–30s.` 계열
- 콘텐츠 길이: 15~30초 (초기 20~27초 테스트)
- 업로드: 미국 피크타임 기준 업로드(ET 기준 저녁/점심 테스트)
- 핵심 지표 우선순위: 저장률 > 시청 유지율 > 공유 > 댓글 > 조회수

## Revenue/Expectations Notes
- 100만 조회 단건 수익은 변동성 큼. 단건 광고수익보다 팔로워 증가/브랜드 협업으로 확장되는 구조가 중요.
- 월 3,000만+는 단일 바이럴보다 반복 가능한 시스템(포맷, 제작, 배포, 협업, 상품화)이 핵심.

## Platform & Account Safety Notes
- "미국 타겟 = 미국 IP 필수"는 필수 조건 아님.
- IP/VPN 조작보다 아래가 더 중요:
  - 영어 텍스트/자막/캡션/바이오 일관성
  - 미국 타임존 업로드
  - 초기 비정상 행동(과도한 팔로우/좋아요/DM/로그인 전환) 회피
  - 저작권 안전한 음원 사용

## Content System (Operating Baseline)
1. Hook (0~2s): 감정 자극 1문장
2. Middle (3~18s): 시네마틱 장면 + 음악
3. Emotion line (18~25s): 여운 문장
4. CTA (마지막): 저장/팔로우/댓글 유도 1문장

## Visual Direction (From Created Image)
- 9:16 세로, 야간 도시, 젖은 아스팔트 반사광
- 로우 앵글, 강한 명암, teal & orange
- 뒤에서 달리는 인물 실루엣 + 차량 모션 블러

## Session-End Logging Rule (IMPORTANT)
앞으로 세션이 끝날 때마다 이 파일의 `## Session Log` 섹션에 새 항목을 추가한다.

로그 포맷:
- Date/Time (KST)
- What was done
- Key decisions
- Outputs created/updated
- Next actions (top 1~3)

## Session Log
### 2026-03-02 19:xx KST
- What was done: 기존 ChatGPT 대화 전체 맥락을 실행 메모로 구조화해 `agent.md` 생성.
- Key decisions:
  - 미국 타겟 숏폼 운영 방향 유지
  - 계정 보안/정책 준수 중심 운영
  - 세션 종료 시 누적 로그 유지 규칙 확정
- Outputs created/updated:
  - `/Users/dong-u/Documents/해외인스타/agent.md`
- Next actions:
  1. 실제 사용할 계정명 확정
  2. 프로필(Bio/카테고리/핸들) 3플랫폼 통일
  3. 첫 10개 숏폼 스크립트/훅 제작

### 2026-03-02 19:23 KST
- What was done: GitHub 저장소(`gdw8119/insta_marketing`) 동기화 시도를 시작하고 로컬 Git 상태 확인 수행.
- Key decisions:
  - 현재 환경에서 `/usr/bin/git` 실행 시 Command Line Tools 미설치 오류로 진행 불가 판단
  - 도구 설치 후 동일 절차(원격 연결 → 커밋 → 푸시) 재시도 필요
- Outputs created/updated:
  - `/Users/dong-u/Documents/해외인스타/agent.md` (세션 로그 추가)
- Next actions:
  1. macOS Command Line Tools 설치
  2. 설치 확인 후 원격 저장소 연결
  3. `agent.md` 커밋/푸시로 동기화 완료

### 2026-03-02 19:29 KST
- What was done: Git 동기화 실행(로컬 저장소 초기화, 원격 등록, 커밋 생성) 후 GitHub 푸시 시도.
- Key decisions:
  - 로컬 Git 저장소 생성 및 `main` 브랜치 사용
  - 원격 `https://github.com/gdw8119/insta_marketing.git` 연결
  - 인증 미구성 상태로 자동 푸시는 보류
- Outputs created/updated:
  - 로컬 Git 커밋: `1a0aaba` (`docs: add instagram overseas marketing working memory`)
  - `/Users/dong-u/Documents/해외인스타/agent.md` (세션 로그 추가)
- Next actions:
  1. GitHub 인증 방식 설정(HTTPS credential helper 또는 SSH 키)
  2. `git push -u origin main` 실행
  3. 원격 저장소 반영 확인

### 2026-03-02 19:54 KST
- What was done: Git 인증 이슈 해결 후 동기화 재개 준비 상태 점검(`main` ↔ `origin/main` 확인) 및 누락 로그 정리.
- Key decisions:
  - 로컬 변경분은 `agent.md`만 커밋/푸시
  - 시스템 파일(`.DS_Store`)은 동기화 대상에서 제외
- Outputs created/updated:
  - `/Users/dong-u/Documents/해외인스타/agent.md` (세션 로그 추가)
- Next actions:
  1. `agent.md` 커밋
  2. 원격(`origin/main`) 푸시
  3. 동기화 완료 상태 확인
