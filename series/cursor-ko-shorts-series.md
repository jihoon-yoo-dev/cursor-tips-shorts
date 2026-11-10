# Cursor 한글 Shorts 시리즈 — 시리즈 바이블

**잠금일:** 2026-11-09  
**Project:** Jihoon  
**관련:** `preferences.md` (Cursor 한글 Shorts 시리즈) · `docs/cursor-usage-diagnosis.md` · `docs/episode-01-cursor-ko-short-package.md`  
**GitHub (문서 아카이브):** https://github.com/jihoon-yoo-dev/cursor-tips-shorts — public · Ep 폴더는 `episodes/epNN/` · **미디어(mp4/mp3)는 올리지 않음** (YouTube/로컬). Ep2+ 패키지·캡션·시드도 여기 push.

---

## 1. Intent (왜 하는가)

매일 **아주 작은 Cursor 습관 하나**를 익히고, 그 장면을 **한국어 YouTube Short**로 남긴다.

| 층 | 목표 |
|----|------|
| **습관** | **하루 1팁** — 실제로 쓰는 클릭·파일·에이전트 흐름 (가급적 매일 1 Short) |
| **영상** | 한국 시청자(초보·중학생도 이해 가능)가 따라 할 수 있는 Short |
| **제작자 성장** | 매 Episode로 Jihoon도 숨은 Cursor/AI 기능을 같이 익힘 |
| **확장** | 같은 영상에 **영어 soft caption만** (더빙 없음) |
| **수익** | DIY Founder 채널 플레이리스트로 쌓아 채널·YPP에 기여 |

KPI는 “기능 백과”가 아니라 **시청자가 오늘 한 번 써 보는 것** + **제작자가 한 기능 더 익히는 것**.

---

## 2. DIY Founder와의 관계

| | **DIY Founder** | **Cursor 한글 Shorts** |
|--|-----------------|------------------------|
| 언어 | 영문 우선 | **한국어 우선** |
| 주제 | News Signal MVP · AI 파운더 under the hood | Cursor 도구 습관 1개/편 |
| 에피소드 | Episode N (영문 채널) | Episode N (한글 시리즈) |
| 제작 | faceless + edge-tts 파이프라인 강함 | **Cursor 화면 + KO TTS 나레이션** (얼굴 출연 없음) |

**확정 (2026-11-09):** 채널은 기존 **`@DIY-Founder` (DIY Founder)**. Cursor 한글 Shorts는 **새 전용 플레이리스트**에만 모아 둔다. 영문 News Signal Episode와는 시리즈·제목·썸네일·설명을 섞지 않는다.

| 항목 | 결정 |
|------|------|
| 채널 | DIY Founder (`@DIY-Founder`) |
| 보관 | **신규 플레이리스트** (시리즈 전용) |
| 새 채널 | 만들지 않음 |

### 플레이리스트 제목 (후보 → 권장)

| 순위 | 제목 | 왜 |
|------|------|-----|
| **권장** | **Cursor 활용법** | 검색어 `Cursor` + “어떻게 쓰는지”가 바로 보임. 짧고 시리즈 확장에 무난 |
| 2 | Cursor AI 실전 팁 | AI·실전 강조. 약간 길음 |
| 3 | Cursor 초보 가이드 | 초보 타깃 명확. 중급 팁 후반엔 제목이 좁아 보일 수 있음 |
| 4 | 매일 Cursor 1팁 | 리듬·약속이 보임. “매일”을 못 지키면 부담 |
| 5 | Cursor Tips (한글) | 영문 채널과 공존 시 구분 쉬움. 한글 검색엔 약함 |

**잠금 전 기본값:** Studio에 **`Cursor 활용법`** 으로 생성. Jihoon이 다른 번호로 바꾸면 이 표만 갱신. URL 생기면 아래에 붙인다.  
`플레이리스트 URL:` _(미정)_

---

## 3. Episode 네이밍

- 사용: **Episode 1, Episode 2, Episode 3…** (Ep.01 / Ep.02 OK)  
- **금지:** Day 1 / Day 2 / Day N (DIY Founder와 동일 규칙)  
- 제목 예: `Cursor Context에 남기면 안 까먹어요 (Episode 1)`  
- `#shorts`는 제목이 아니라 설명·해시태그

시리즈 순서는 `docs/cursor-usage-diagnosis.md`의 **Strong → Partial → Gap**을 따른다.  
잘 쓰는 습관부터 보여 주고, 약한/안 쓰는 기능은 후반에 학습·데모한다.

---

## 4. Production rules

1. **한국어 first** — **프로그램 TTS로 한국어 음성 생성·믹스** + **burn-in 한글 자막**.  
2. **영어 = 자막만** — Studio soft CC / `.srt` EN. **영어 더빙·2트랙 오디오 없음.** 의미 미러, 직역 금지.  
2b. **본인 음성 (나중)** — JHN-46 연구. Ep1·일상은 TTS.  
3. **화면** — **최신 Cursor UI + 나레이션**. 얼굴 없음.  
   **데모 Project (잠금):** 개인 Jihoon 화면 금지. 시리즈 전용 **가짜 Agent Project**의 Context/`preferences`/`docs`만 촬영. 컨셉 일러스트만으로는 제작하지 않음.  
4. **길이** — **YouTube Shorts 허용 길이 안** (실무 목표 **≤60초**, 여유 있으면 45–60초). 차분하되 Shorts 밖으로 안 나감.  
5. **한 Short = 팁 하나** — 두 번째 팁은 다음 Episode.  
6. **구조 (잠금, Jihoon 합의 2026-11-09)**  
   - **0–3초 훅:** 이 Episode가 푸는 **문제** 또는 **한 줄 가치**를 먼저 말함. (“무엇을 / 왜 보면 되는지”)  
   - **그다음 본문:** 초고속 컷 경쟁 안 함. **짧고·쉽고·천천히**, 실제 Cursor 화면 예시로 해결책 1개만.  
   - 훅과 본문 **약속이 같아야 함** (훅만 자극적이고 본문이 다른 팁이면 이탈·불신).  
7. **템포 / TTS (잠금 2026-11-09)** — 시리즈 기본 음성 **`ko-KR-InJoonNeural` @ −5%** (Ep1 최종 믹스와 동일).  
   −15%는 너무 느리고 부자연스럽다는 Jihoon 피드백으로 **폐기(기본값 아님)**.  
   UI 단어 뒤 짧은 멈춤·클릭은 따라올 속도 유지. 침묵 늘리기 ≠ 친절; 군더더기 문장은 자른다.  
8. **쉬운 말** — 초등·중학생도 따라올 문장. 은어는 화면 가리키며 한 번만 풀어 씀.  
9. **과장·낚시 금지** — 정보·증명 톤. 훅은 자극이 아니라 **정확한 가치 한 줄**.  
10. **프라이버시** — 가족명·주소·키·토큰 화면 노출 금지.  
11. **주기** — **가급적 하루 1편**. 못 한 날은 다음날 1편만 (몰아찍기 강요 금지). 연속보다 **매편 완주 가능한 품질**.

DIY Founder 영문 파이프라인(`generate_short.py` + `edge-tts` 등)을 **한국어 TTS + InJoon −5%**로 확장. 화면 = 실 Cursor UI, 목소리 = 생성 시 프로그래밍 첨가.

---

## 5. Publishing checklist (집 세션)

집 도착 후, 녹화 전에 AI와 **짧게 리뷰** → 녹화 → 업로드.

### A. 리뷰 (약 10분, AI와)

- [ ] 오늘 Episode 번호·한 줄 주제 확인 (`cursor-usage-diagnosis.md`)  
- [ ] 훅 0–3초가 **문제/가치 한 줄**인지 · TTS 미리듣기 (**InJoon −5%**, Shorts ≤60초, 군더더기 없음)  
- [ ] burn-in 줄이 Shorts 하단 UI·오른쪽 버튼과 겹치지 않는지  
- [ ] 데모 클릭 순서 3–7컷만 적어 두기  
- [ ] 민감정보/키/개인 채팅이 화면에 안 나오는지  
- [ ] (선택) EN soft caption 문장 훑기  

### B. 녹화

- [ ] Cursor UI 확대·테마 고정 (시청자가 글자 읽히게)  
- [ ] 한 팁만; 옆길로 새면 끊고 다음 Episode로  
- [ ] 훅 첫 3초 = 문제 한 줄  

### C. 업로드 (Studio)

- [ ] 채널: **DIY Founder** (`@DIY-Founder`)  
- [ ] 전용 플레이리스트 **`Cursor 활용법`**(또는 확정 이름)에 추가 · 없으면 생성  
- [ ] 제목 = Episode N 포함, Day 금지 · 영문 News Signal Ep와 제목 혼동 없게  
- [ ] 설명·태그·해시태그 붙여넣기 (패키지 문서)  
- [ ] burn-in 유지 + `.srt`/Studio CC (KO 필수, EN 선택)  
- [ ] 시청자층·공개/예약 확인  
- [ ] 게시 후 URL을 Jihoon Context `docs/` 또는 Done Wall에 1줄 · 플레이리스트 URL도 있으면 시리즈 문서에 기록  

### D. 시리즈 유지

- [ ] `cursor-usage-diagnosis.md`에 “촬영함 / 약점 발견” 한 줄 메모  
- [ ] 다음 Episode 후보만 Next에 올리기 (한 번에 여러 편 촬영 강요 금지)

---

## 6. 문서 맵

| 문서 | 역할 |
|------|------|
| `docs/cursor-ko-shorts-series.md` | 이 바이블 |
| `docs/cursor-usage-diagnosis.md` | 잘 씀 / 부분 / 갭 + Ep 1–8 순서 |
| `docs/episode-01-cursor-ko-short-package.md` | 첫 Short 패키지 |
| `docs/diy-founder-north-star.md` | DIY Founder 수익화 (별 시리즈) |
| `docs/channel-diy-founder.md` | DIY Founder 채널 설정 |

---

## 7. 성공 기준 (시리즈 초반)

- Episode 1이 **실제 Cursor UI**로 올라가 있다  
- 시청자 한 줄 가치가 설명란 첫 줄에 있다  
- Jihoon이 **집 세션에서 AI 리뷰 → 업로드** 루프를 한 번 완주했다  
- Day N 표기가 제목·대본·설명에 없다  
