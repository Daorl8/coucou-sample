# STRUCTURE · coucou-sample

```
coucou-sample/
├─ index.html                  단일 파일 (CSS·JS 인라인)
├─ wrangler.toml               name = coucou-sample → coucou-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore               img/ · 문서 · index_*.html · _deploy 배포 제외
├─ cc-gowun-r.woff2 / cc-gowun-b.woff2   한글 제목 (고운바탕 400 · 700, 쓰는 글자만)
├─ cc-instrument-italic.woff2  영문 소제목 (Instrument Serif Italic, 라틴만)
├─ cc-pretendard.woff2         본문 (Pretendard 400–700)
├─ cc-cats.webp / cc-cats-w.webp   고양이+지붕 선화 (헤더 · 푸터 흰색)
├─ cc-logo.webp                고양이 + coucou bakery cafe 전체 (Our Story)
├─ cc-house.webp               히어로 외관
├─ cc-cups.webp / cc-mycats.webp   Our Story 컵 · 사장님 고양이
├─ cc-pizza / sand / gratin / soup / bowl / toast .webp    Brunch (피자 · 샌드위치 · 샥슈카 · 수프 · 그릭요거트 · 오픈리코타)
├─ cc-coffee-1 ~ 3.webp                                    Coffee (추출 과정)
├─ cc-wc-1 ~ 9.webp                                        Whole Cake (캡션 없음)
├─ cc-bake-1 ~ 5.webp                                      Bake & Gift
├─ cc-sp-1 ~ 6.webp                                        Garden House (a~f)
├─ favicon.png · og-coucou.jpg
├─ img/                        원본 (배포 제외). 하위 폴더 brunch_coffee_cat · cake · gift · outside = 사장님 직접 제공 (2026-11-11)
├─ _old/                       교체된 옛 사진 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#story`(mist) → `#brunch` → `#coffee`(먹색) → `#cake`(mist) → `#bake` → `#space`(mist) → `#visit` → 푸터(먹색) + 모바일 `.quick`.

## 링크 한곳 정리
- 케이크 예약: `m.place.naver.com/restaurant/1326613374/booking` (헤더 · 히어로 · 케이크 섹션 · 하단 바 4곳)
- 단체 주문 문의(#bake): 임시로 같은 예약 탭. 단체예약 전용 주소 받으면 이 1곳만 교체
- 길찾기: `map.naver.com/p/entry/place/1326613374` · 전화 `070-8064-8511` · 인스타 `@coucou_bakerycafe`

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). Instrument Serif엔 한글 없음 → 이탤릭 영문 속 한글은 `<span class="ko">`.
