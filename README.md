# ⌨️ TOTEM 38-key Typing Trainer

TOTEM 38-key (3×5 col-stagger) 스플릿 키보드 타자연습 웹앱  
실제 키맵: [pikachom/zmk-config-totem](https://github.com/pikachom/zmk-config-totem)

## 실행법

```bash
open index.html   # 브라우저로 바로 열기 (인터넷 불필요)
```

## 기능

- **키보드 시각화** — 실제 TOTEM 물리 레이아웃 (컬럼 스태거 + 썸키 아크)
- **4개 레이어** — BASE / NAV / NUM+SYM / DEVICE 탭 전환
- **5가지 연습 모드** — 영문 / 한글 / 숫자·특수문자 / 혼합 / 코드
- **다음 키 하이라이트** — 입력할 키를 키보드 위에서 실시간 표시
- **손가락 컬러 가이드** — 검지/중지/약지/소지/엄지 색상 구분
- **실시간 통계** — WPM, 정확도, 경과시간, 오류수
- **오류 히트맵** — 자주 틀리는 키 시각화
- **한글 IME 지원** — 조합 중 오류 없음

## 키맵 (pikachom/zmk-config-totem 기준)

| 레이어 | 활성화 | 주요 내용 |
|--------|--------|-----------|
| BASE (0) | 기본 | QWERTY, mod-tap: `,/⌃` `./ ⌥` `//⌘` |
| NAV (1) | 왼 썸키 TAB 홀드 | 방향키, ⌘←→↑↓, ESC, DEL |
| NUM/SYM (2) | 오른 썸키 ENT 홀드 | 숫자 1-0, `-=[]\'()` |
| DEVICE (3) | NAV + NUM/SYM 동시 | 볼륨, 밝기, BT 프로필 전환 |

## TOTEM 적응 팁

1. **중지 열이 가장 높음** — E·D·C 열 기준으로 손을 수직으로 내려찍기
2. **썸키 구분** — 왼 엄지 3개(⌥SPC / ⌘SPC / TAB-NAV), 오른 엄지 3개(ENT-SYM / BSPC / CAPS-DEV)
3. **mod-tap 연습** — `,` `.` `/` 키는 홀드하면 ⌃ ⌥ ⌘ → 코드 모드에서 집중 연습
4. **정확도 우선** — WPM보다 오류율 줄이기가 먼저
