# Episode 1 — Cursor 한글 Short 패키지

**시리즈:** Cursor 활용법 (플레이리스트) · DIY Founder  
**Episode:** 1 (Day 표기 금지)  
**상태:** **최종 Short 재믹스 완료** · YouTube 업로드됨 · 문서 아카이브 GitHub  
**근거:** `docs/cursor-usage-diagnosis.md` Strong #1 · `docs/cursor-ko-shorts-series.md`  
**GitHub:** https://github.com/jihoon-yoo-dev/cursor-tips-shorts/tree/main/episodes/ep01

### 최종 업로드 파일

| 항목 | 내용 |
|------|------|
| **최종 MP4** | `media/ep01_cursor_ko/ep01_final_shorts.mp4` |
| 해상도 | **1080×1920** (소스 1200×1920 → center crop/scale) |
| 길이 | **48.82 s** (≤60) |
| 오디오 | InJoon `ep01_narration_ko.mp3` @ **−5%** · AAC 192k stereo |
| 영상 구성 | 스크린(~34s) → Library/prefs/prompt stills로 잔여 길이 채움 · 약한 Ken Burns |
| KO burn-in | mid-lower · `ep01_ko_burnin.txt` (−5%에 맞게 스케일) |
| EN soft CC | `media/ep01_cursor_ko/ep01_en.srt` (−5%에 맞게 스케일) |
| 백업(느린 −15% 믹스) | `ep01_final_shorts_slow55s.mp4` · `ep01_narration_ko_rate-15.mp3` |
| 얼굴 | 없음 · Cursor Tips Demo UI만 |

### 화면 녹화 (데모 Project · 소스)

| 항목 | 내용 |
|------|------|
| Project | `Cursor Tips Demo` (개인 Jihoon 아님) |
| 파일 | `media/ep01_cursor_ko/screen/ep01_demo_ui_9x16.mp4` |
| 해상도 | **1200×1920** (세로 모니터) · ~34s |
| 샷 | Library(파일/Context) → `preferences.md` → 프롬프트 `Context의 preferences 보고, 오늘 할 일 한 줄만 제안해줘` |
| 참고 | 최신 UI에서 Context 파일 브라우저는 **Library** 탭 |
| 연장 stills | `ep01_frame_library.png` · `ep01_frame_prefs.png` · `ep01_frame_prompt.png` |

---

## 제작 진행 (TTS / CC · 2026-11-10) → **믹스 완료**

| 항목 | 내용 |
|------|------|
| 후보 음성 | `media/ep01_cursor_ko/voice-a.mp3` · `voice-b.mp3` · `voice-c.mp3` |
| **권장 (시리즈 기본)** | **`ko-KR-InJoonNeural` @ −5%** → `media/ep01_cursor_ko/ep01_narration_ko.mp3` |
| 측정 길이 | **48.82 s** (Shorts ≤60 s) · −15% 백업 55.90 s |
| 트림 필요 | **아니요** |
| EN soft CC | `media/ep01_cursor_ko/ep01_en.srt` (−5% 타이밍 스케일) |
| KO burn-in | `media/ep01_cursor_ko/ep01_ko_burnin.txt` |
| 보이스 노트 | `media/ep01_cursor_ko/VOICE_NOTES.md` |
| **믹스 노트** | Jihoon 피드백으로 −15%→−5% 재생성. 화면(~34s)+stills. 최종 `ep01_final_shorts.mp4` **48.82s** / 1080×1920 |

후보 요약: InJoon 55.90 s / SunHi 50.88 s / HyunsuMultilingual 51.00 s (모두 −15%).  
플레이리스트 URL은 Studio 확인 후 이 문서에만 추가.

### 잠금 (Jihoon 2026-11-09)
- **영상 제목:** `Cursor가 까먹을 때 Context에 남기세요 (Episode 1)`
- **플레이리스트:** `Cursor 활용법` — Studio에 **이미 생성됨** (URL 있으면 문서에 추가)
- **UI:** **최신 Cursor IDE / Project Context UI** 기준으로 촬영 (구버전 메뉴 이름·레이아웃 금지)

---

## 주제 (ONE)

**채팅만 믿지 말고, Cursor Context(문서)에 한 줄 남기기**

**왜 Ep1인가:** Project에서 가장 자주 쓴 습관이 `preferences.md`·`docs/`에 결정을 남기는 것. 클릭 적고, “AI가 까먹어요”에 바로 답함.

---

## 제목 (확정)

**확정:** `Cursor가 까먹을 때 Context에 남기세요 (Episode 1)`

(참고용 폐기 후보: 채팅 말고 파일에… / AI 장기 기억은 Context 탭에…)  
`#shorts`는 제목에 넣지 않음.

---

## 훅 (첫 3초) + 전체 구어 대본 (Shorts ≤60초, 차분 템포)

### 훅
> “Cursor랑 어제 얘기한 거… 오늘 왜 몰라요?”

### 전체 대본 (한국어 TTS · 시리즈 기본 −5% · 목표 ≤60초)

채팅은 금세 길어지고, 모델은 예전 말을 다 들고 있지 않아요.  
그래서 저는 Cursor **Project의 Context**에 남깁니다.  
중요한 규칙은 `preferences` 같은 파일에 한 줄.  
긴 설명은 `docs` 폴더에 문서로.  
다음에 에이전트에게 “Context 보고 이어서”라고만 하면,  
어제 합의한 역할·언어·금지 사항이 다시 붙어요.  
오늘 습관 하나: 결정 나면 채팅에만 두지 말고, Context에 한 줄 저장.  
구독하면 Episode 2에서 Cloud Agent에 일 맡기는 법 이어갈게요.

*(끝 — CTA는 담백하게. 과장 없음.)*

**음성 (잠금·업데이트):** `ko-KR-InJoonNeural` @ **−5%** → `media/ep01_cursor_ko/ep01_narration_ko.mp3` (**48.8초**). (−15% 백업 있음)  
**화면:** **Cursor Tips Demo** Project만 · 개인 Jihoon 화면 금지 · 얼굴 없음. **영어:** soft CC만.  
**더미 Context 시드:** `docs/demo-seed/` (`preferences.md`, `docs/welcome.md`, `docs/episode-01-note.md`).

---

## Burn-in 자막 (짧은 KO)

Shorts 하단 UI·오른쪽 스택 피해서 **중하단**에 짧게.

| 초(대략) | 화면 문구 |
|----------|-----------|
| 0–3 | 어제 말한 거… 오늘 몰라요? |
| 3–8 | 채팅 ≠ 장기 기억 |
| 8–16 | Project → Context |
| 16–24 | preferences에 한 줄 |
| 24–32 | docs에 길게 |
| 32–40 | “Context 보고 이어서” |
| 40–48 | 결정 = 파일에 저장 |
| 48–55 | Ep.2: Cloud Agent |

한 줄 최대 ~14자 권장. 문장 전체를 burn-in에 넣지 말 것.

---

## Optional English soft caption / Studio CC

의미 미러 (직역 금지). burn-in은 KO 유지, Studio에 EN 트랙 추가할 때:

> Cursor forgets long chats. I don’t rely on the thread alone.  
> I save decisions in this Project’s Context — short rules in preferences, longer notes under docs.  
> Next time I say “continue from Context,” the agent picks up our role, language, and don’ts.  
> One habit today: when you decide something, write one line in Context.  
> Subscribe for Episode 2 — handing work to a Cloud Agent.

---

## Screen demo shot list (최신 Cursor UI)

**필수:** Cursor를 **최신 버전으로 업데이트**한 뒤 촬영. 구 UI(옛 사이드바 이름·옛 Agents 레이아웃) 쓰지 말 것.  
프라이버시: 가족명·주소·키·민감 채팅이 프레임에 안 나오게.

| # | 화면 (최신 UI 기준) | 클릭/동작 |
|---|---------------------|-----------|
| 1 | Cursor 데스크톱 · **Jihoon Project** 열린 채팅 | 창 제목/프로젝트 이름만 보이게. 채팅 본문은 가리거나 스크롤 |
| 2 | Project **Context** 패널 (앱 내 Context 탭) | Context 열기 → 파일 목록이 크게 보이게 확대 |
| 3 | `preferences.md` | **비민감** 줄만 (예: Language Korean / 역할). 스크롤로 민감 줄 제외 |
| 4 | `docs/` | 폴더·파일명만 스치기 (`cursor-ko-shorts-series.md` 등) |
| 5 | 채팅 입력창 | `Context의 preferences 보고, 오늘 할 일 한 줄만 제안해줘` 입력 |
| 6 | 에이전트 답 일부 | Context/preferences를 인용하는 짧은 답만 |
| 7 | (선택) preferences에 bullet 한 줄 추가 | “결정 저장” 제스처 2초 |

핵심 컷 = **2 → 3 → 5**. 마우스·메뉴 **확대(디스플레이 확대 또는 줌)** 필수.

---

## CTA

- 구독 + “Episode 2: Cloud Agent에 맡기기”  
- 좋아요·댓글 강요 없음.  
- “인생 변경 / 무조건” 류 금지.

---

## Upload metadata

**채널:** DIY Founder (`@DIY-Founder`)  
**플레이리스트:** **`Cursor 활용법`** (Studio에 생성 완료 · URL 있으면 여기 추가)

### Description (복붙)

```text
Cursor 채팅만 믿으면 예전 결정을 놓치기 쉽습니다.
이 Short는 Project Context(preferences / docs)에 한 줄 남기는 습관입니다.

Episode 1 · 플레이리스트: Cursor 활용법
채널: DIY Founder · 다음: Episode 2 — Cloud Agent에 일 맡기기

This Short is Korean-first. Optional English captions in Studio.
Educational — not financial advice.

#shorts #Cursor #AI #개발자 #생산성
```

### Tags (KO + EN light)

`Cursor`, `Cursor AI`, `Context`, `프로젝트`, `에이전트`, `AI 코딩`, `쇼츠`, `생산성`, `개발`, `Cloud Agent`, `Episode 1`

### Hashtags

`#shorts` `#Cursor` `#AI` `#개발` `#생산성` `#에이전트`

---

## Home review checklist (녹화 전 10분, AI와)

1. [ ] 주제가 **Context 한 팁**만인지 (워커·Skills 섞지 않기)  
2. [ ] TTS 미리듣기로 재기 → **Shorts ≤60초**, 숨 가쁘지 않은지  
3. [ ] 훅 첫 문장이 문제(까먹음)인지  
4. [ ] burn-in 줄이 하단 UI와 안 겹치는지  
5. [ ] `preferences` 화면에 **민감 정보 없음**  
6. [ ] 데모 클릭 순서 1→5 리허설 1회  
7. [ ] 제목에 **Episode 1**, Day 없음  
8. [ ] (선택) EN CC 문장 한 번 읽기  
9. [ ] 녹화 해상도·커서 화살표 보이게 확대  
10. [ ] DIY Founder에 업로드 + **`Cursor 활용법`** 플레이리스트에 넣고 URL을 Done Wall / Context에 1줄  

---

## 완료 후

- 게시 URL을 이 문서 상단 **상태**에 추가  
- `cursor-usage-diagnosis.md` Ep1 행에 “게시함” 메모  
