# 숙암향우회 · 270107_Sukam 스마트 가이드북

2027년 1월 7일 출발 **푸꾸옥 3박5일(LJ)** / **오키나와 3박4일(ZE)** 중 선택용 듀얼 옵션 가이드북입니다.

## 배포

- GitHub Pages: `https://indadady.github.io/270107_Sukam/`
- 로컬 확인: `index.html`을 브라우저에서 열기 (또는 간단한 정적 서버)

## 구조

| 경로 | 설명 |
|------|------|
| `index.html` | 단일 페이지 가이드북 (Tailwind CDN, Leaflet) |
| `assets/images/` | 행사·일정별 사진 (pqc-*, oki-*, og-thumb 등) |
| `assets/IMAGE_CREDITS.md` | 이미지 출처 요약 |

## 개발 메모

- `_build.py`, `_assemble.py`, `_part*.html`은 생성용 보조 파일입니다 (`.gitignore`의 `_build*` 패턴).
- 재빌드: `python _assemble.py`
- 일정 테스트: URL `?test_date=2027-01-08` 또는 스크립트 내 `TEST_DATE`

## 담당

- 숙암향우회 배부근 대표 010-9362-8265
- 투어메이커 이재명 010-9443-7881 · 조혁 010-4249-4026 · 033-562-2551
