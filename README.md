# cssharing 마케팅 OS — 대시보드

> [Private 본체 레포](https://github.com/cssharing/cssharing-marketing-os)의 외부 공개 대시보드

## 🌐 보기

**GitHub Pages**: https://cssharing.github.io/cssharing-os-dashboard/

## 📦 이 레포에 들어 있는 것

- `index.html` — 정적 대시보드 UI (Tailwind CDN, Pretendard 폰트)
- `README.md` — 이 파일

## 🔒 보안 — 무엇이 여기 있고, 없는가

이 레포는 **공개 영역**입니다. 누구나 코드를 볼 수 있습니다.

### ✅ 공개 OK
- 6부서 카드 (이름·역할·Phase 상태)
- 외부 시스템 연결 상태 (이름만, ID 없음)
- 영감 자료 외부 링크
- 운영 통계 합계 (Phase 1+ 추가 예정)
- 폴더 구조·헌법 일부

### ❌ 절대 들어가지 않음
- API 키, OAuth 토큰
- 시트 ID·드라이브 폴더 ID
- 고객 데이터·리드 raw
- 광고비·매출 raw 금액
- 봇 코드·스킬·헌법 본문

> 본체 코드·데이터는 별도 [Private 레포](https://github.com/cssharing/cssharing-marketing-os) 에 있고, 이 Public 레포로는 가공된 요약만 동기화됩니다 (Phase 1+ 자동 파이프라인).

## 🛠 갱신 방법

현재는 정적 데이터 (JS 객체). Phase 1+에 자동 동기화 (`sync-to-pages.yml`) 추가 예정.

## 📚 영감

- [뽀짝이의 방](https://www.gpters.org/ax-lab/post/tour-cats-house-1-GjegRI69VrZ9Hzt) — 워크스페이스 구조
- [Lesson 11](https://bbojjak-library.gpters.org/lessons/lesson-11) — 자율성 메커니즘
- [Lesson 13](https://bbojjak-library.gpters.org/lessons/lesson-13) — HTML 카드 자동화
- [Lesson 17·18·20](https://bbojjak-library.gpters.org/lessons/lesson-17) — 보안·동기화 패턴

---

**제작**: cssharing · Claude Code 기반
