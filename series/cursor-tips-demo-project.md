# Cursor 활용법 — 데모 Project 설계

**잠금:** 2026-11-09 · 옵션 A  
**목적:** 민감 정보 없이, 최신 Cursor UI로 Shorts를 찍기 위한 **가짜 Agent Project**

---

## Cursor가 “자기 UI”를 조작할 수 있나?

| 경로 | 가능? | 설명 |
|------|-------|------|
| 이 Jihoon 클라우드 채팅이 네 Mac Cursor 창을 원격 조작 | **아니오** | 클라우드 에이전트는 네 데스크톱 마우스를 직접 잡지 못함 |
| Mac Mini **self-hosted worker**가 로컬에서 클릭·화면 녹화 | **조건부 예** | 같은 Mac에서 에이전트 실행 + macOS **손쉬운 사용(Accessibility)**·화면 기록 권한 필요. UI 바뀌면 깨지기 쉬움 |
| 데모용 Context 파일·대본·TTS·편집 | **예 (기본)** | 파일/에셋은 여기서 전부 생성 가능. Project **생성 클릭 1번**만 사람/로컬 자동화 |

**실무 권장:** 데모 Project는 우리가 내용으로 채우고, **첫 Project 생성·권한 허용**만 네가 하거나 Mac 워커에 한 번 맡긴다. 매 Episode마다 네 개인 Cursor를 켤 필요는 없음.

---

## 데모 Project 스펙

- **이름 (권장):** `Cursor Tips Demo`
- **용도:** 플레이리스트 `Cursor 활용법` 전용. 개인·PictureUs·가족 정보 **절대 넣지 않음**
- **언어:** 데모 `preferences`는 한국어 규칙 예시(교육용 더미)
- **Ep1에 넣을 파일 (더미):**
  - `preferences.md` — 역할/언어/짧은 규칙만 (민감 없음)
  - `docs/welcome.md` — “이 Project는 Shorts 데모용”
  - `docs/episode-01-note.md` — Context에 남긴 결정 예시 한 줄

Ep2+ 는 같은 Project에 Cloud Agent·Skills 등 **에피소드별 더미 파일**만 추가.

---

## 제작 파이프라인 (목표)

1. `Cursor Tips Demo` Project 생성 (UI 1회)
2. Context에 에피소드용 더미 문서 채움 (에이전트)
3. (선택) Mac 워커가 최신 Cursor에서 Context 클릭 경로 녹화
4. 기존 KO TTS + burn-in + EN srt와 합성 → Shorts 업로드

---

## 진행 (2026-11-09 · America/Denver)

- [x] InJoon TTS 잠금 — 시리즈 기본 **`ko-KR-InJoonNeural` @ −5%** (Ep2+ 동일)  
- [x] Ep1 더미 시드: `docs/demo-seed/preferences.md`, `docs/welcome.md`, `docs/episode-01-note.md`  
- [x] **화면 기록** OK · **Device Control and Data Access**(구 Accessibility)로 UI 자동화 OK  
- [x] **`Cursor Tips Demo` Project** 생성됨 (Agent Store `bc-02db868a-…`)  
- [x] Context 시드 복사: `preferences.md` + `docs/welcome.md` + `docs/episode-01-note.md`  
- [x] Ep1 UI 녹화: Library → `preferences.md` → 채팅 프롬프트  
  - **메인:** `media/ep01_cursor_ko/screen/ep01_demo_ui_9x16.mp4` (1200×1920, ~34s)  
  - 최신 UI에서 Context 파일 목록은 **Library** 탭으로 보임  

참고: 녹화 중 Mac을 건드리면 AX 클릭과 겹침 — hands-off 권장.
