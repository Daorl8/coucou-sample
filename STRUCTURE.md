# STRUCTURE · coucou-sample

```
coucou-sample/
├─ index.html                  단일 파일 (CSS·JS 인라인)
├─ wrangler.toml               name = coucou-sample → coucou-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore               img/ · 문서 · index_*.html · _deploy 배포 제외
├─ cc-hahmlet.woff2            한글 제목 (Hahmlet 500–700, 쓰는 글자만)
├─ cc-instrument-italic.woff2  영문 소제목 (Instrument Serif Italic, 라틴만)
├─ cc-pretendard.woff2         본문 (Pretendard 400–700)
├─ cc-cats.webp / cc-cats-w.webp   고양이+지붕 선화 (헤더 · 푸터 흰색)
├─ cc-logo.webp                고양이 + coucou bakery cafe 전체 (Our Story)
├─ cc-house.webp               히어로 외관
├─ cc-cups.webp                Our Story 컵
├─ cc-sand / toast / gratin / bowl / soup / drinks .webp   Brunch
├─ cc-cake-fig / fruit / straw / melon .webp               Whole Cake
├─ cc-tart / fin / gift .webp                              Bake & Gift
├─ cc-garden / path / room / night .webp                   Garden House
├─ favicon.png · og-coucou.jpg
├─ img/                        다올 제공 원본 185장 (배포 제외 · 헬로키티 등 포함, 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#story`(mist) → `#brunch` → `#cake`(mist) → `#bake` → `#space`(mist) → `#visit` → 푸터(진녹) + 모바일 `.quick`.

## 링크 한곳 정리
- 케이크 예약: `m.place.naver.com/restaurant/1326613374/booking` (헤더 · 히어로 · 케이크 섹션 · 하단 바 4곳)
- 길찾기: `map.naver.com/p/entry/place/1326613374` · 전화 `070-8064-8511` · 인스타 `@coucou_bakerycafe`

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). Instrument Serif엔 한글 없음 → 이탤릭 영문 속 한글은 `<span class="ko">`.
