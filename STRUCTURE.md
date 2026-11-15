# STRUCTURE · cafe_armoire-sample (v0.1)

```
cafe_armoire-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = cafe-armoire-sample → cafe-armoire-sample.lgt3232.workers.dev
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ ar-caslon.woff2            영문 제목 (Libre Caslon Display 400, 대문자 포함)
├─ ar-notoserif.woff2         한글 제목 · 문장 (Noto Serif KR 500–600, 페이지 글자 전부)
├─ ar-pretendard.woff2        본문 · 버튼 (Pretendard 400–600, 페이지 글자 전부)
├─ ar-logo.svg / ar-logo-w.svg 로고 (잉크 #2A1E1C / 크림, potrace 벡터)
├─ ar-hero.webp               히어로 · 홀 전체 (4:5)
├─ ar-sofa · ar-door .webp    No.01 Story (소파 · 초록 장롱 문)
├─ ar-basque · ar-sweetpotato · ar-financier .webp   No.02 Signature
├─ ar-rooftop · ar-window · ar-cappuccino · ar-latte · ar-tables · ar-bar .webp   No.03 Vintage Rooms (PC: 루프탑 2×2)
├─ ar-mug · ar-mugs .webp     No.04 Online Store
├─ favicon.png · og-ar.jpg
├─ img/                       다올 제공 원본 56장 (배포 제외 · 얼굴 · 다른 브랜드 포함, 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```
※ 서브셋은 공백 U+0020 · U+00A0 포함(R-6).

## 섹션 순서
헤더(+ 900px 미만 `.snav`) → 히어로 → `#story` → `#menu` → `#space`(초록 띠) → `#shop`(스토어 + 대관) → `#visit` → 푸터(짙은 레드) + 모바일 `.quick`.

## 필수 버튼 (사장님 요청)
- 네이버 플레이스 `https://m.place.naver.com/restaurant/1872641035/home`: 헤더 · 히어로 · 메뉴 안내 · 오시는 길 · 푸터 · 하단 바
- 스마트스토어 `https://smartstore.naver.com/cafearmoire`: 히어로 · 스토어 섹션 · 푸터 · 하단 바
- 전화 `tel:024639981`(02-463-9981): 히어로 · 대관 · 오시는 길 · 푸터 · 하단 바
- 그 밖: 네이버 길찾기 `map.naver.com/p/entry/place/1872641035` · 인스타 `https://www.instagram.com/cafe_armoire/`(대관 DM · 푸터)

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 한글은 명조 · Pretendard 둘 다, 영문 제목 폰트는 대문자까지 포함.
