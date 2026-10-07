# 신경해부학 학습 허브 (2026-2)

안산대학교 물리치료학과 신경해부학 강의록 Ch01~Ch13 핵심요약을 한곳에 모은 학생용 페이지입니다. 심경섭 교수 제작.

- 허브: https://neuroanat-hub.vercel.app/
- 챕터 요약본: GitHub 저장소 `NA-ch01`, `NA-ch02` … 의 배포 주소 (Ch01~Ch03은 Pages, 예: https://gssim11.github.io/NA-ch01/ · Ch04는 Vercel https://na-ch04.vercel.app/)
- 캠퍼스 메타버스 신경해부학관은 이 허브 한 곳만 링크합니다.

## 챕터를 새로 공개할 때

`index.html`의 `CHAPTERS` 배열에서 해당 챕터의 `url`만 채우고 커밋하면 Vercel이 자동으로 다시 배포합니다. `url`이 비어 있으면 카드가 "준비 중"으로 표시되고, 진도 바는 채워진 `url` 개수로 계산됩니다. 메타버스는 손대지 않습니다.

```js
{n:5, kr:"바닥핵", ..., slides:27, url:"https://<Ch05 배포 주소>/"},
```

## 파일

- `index.html` — 허브 페이지 (외부 리소스 없음, 단일 파일)
- `og-image-hub.png` — 카카오톡·LMS 링크 미리보기 이미지 (1200×630)
