# 자원봉사센터 전환 길잡이

민간중심 자원봉사센터 전환 표준 가이드북(v103)을 주제·유형별로 찾아볼 수 있는 정적 웹페이지입니다.

## 구성

| 파일 | 설명 |
| --- | --- |
| `index.html` | 진입 페이지 |
| `style.css` | 스타일 |
| `app.js` | 화면 전환·검색·유형 찾기·준비도 체크 |
| `content.js` | 가이드북 본문 데이터 |
| `icon.svg` | 파비콘 |

빌드 과정 없이 정적 파일만으로 동작합니다.

## GitHub Pages로 공유하기

1. 저장소 **Settings → Pages** 로 이동합니다.
2. **Build and deployment → Source** 를 `Deploy from a branch` 로 두고, 브랜치와 `/ (root)` 폴더를 선택한 뒤 **Save** 합니다.
3. 잠시 뒤 `https://nvc1365.github.io/vc-transition/` 에서 페이지를 볼 수 있습니다.

## 로컬에서 보기

```bash
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000` 을 엽니다.
