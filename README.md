# 🍉 워터멜론 슬라이드 (Watermelon Slide)

수박 튜브를 탄 코기가 굽이치는 워터슬라이드를 내려가 수영장에 다이빙하는 캐주얼 웹 게임입니다.
**순수 HTML5 Canvas + JavaScript**로 만들어졌으며, 외부 라이브러리나 빌드 도구가 전혀 없습니다.

## 🎮 플레이 방법

- **좌우 이동**: 화면을 드래그하거나 `←` `→` 방향키
- **점프**: 점프 구간에서 `JUMP` 버튼 또는 `Space` 키 (끊긴 구간을 뛰어넘기)
- **정중앙 보너스**: 슬라이드 한가운데를 유지하면 보너스 점수가 쌓입니다
- **다이빙**: 슬라이드 끝에서 골드존(가운데)에 가깝게 입수할수록 높은 점수

## ✨ 특징

- 총 **10라운드** — 갈수록 길고, 빠르고, 점프 구간이 많아짐 (최대 6회)
- 곡선 + 뱅킹(회전) 슬라이드 연출
- 점프 구간 **화살표 예고 + 남은 횟수 표시**
- 상태별 캐릭터 스프라이트 (슬라이드 / 점프 / 다이빙)
- 다이빙 점수 팝업, **라운드당 최대 100점**
- 닉네임 입력 + **로컬 랭킹**(브라우저 localStorage 저장)
- 모바일 세로 화면 최적화

## 🚀 실행 방법

`index.html` 한 파일이면 됩니다 (이미지가 모두 내장된 자체 완결형 파일).

- **로컬**: `index.html`을 브라우저로 바로 열기
- **GitHub Pages**: 저장소 루트에 `index.html`을 올린 뒤
  `Settings → Pages → Deploy from a branch → main / (root)` 설정
  → `https://<username>.github.io/<repo-name>/` 에서 플레이

## 🛠 기술

- HTML5 Canvas 2D (가짜 3D / scanline 원근 투영)
- 순수 JavaScript (프레임워크·CDN 없음)
- 점수 랭킹은 `localStorage`에 저장 (서버 불필요)

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
