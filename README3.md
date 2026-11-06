# 2026 천안시 청년정책 · 웹 프레젠테이션

첨부된 PowerPoint 10장을 **원본 슬라이드 이미지(WebP)** 로 보존한 정적 웹사이트입니다. 원본 수치·사업명·디자인을 유지하며, 슬라이드 탐색/원본 기반 정보패널/출처 링크/반응형 레이아웃을 제공합니다.

## 파일 구성
- `index.html`: 메인 페이지
- `style.css`: 디자인 및 반응형
- `app.js`: 슬라이드 전환·키보드·터치·정보패널·차트
- `data.json`: 슬라이드별 원문 핵심 정보와 출처
- `assets/slide-01.webp` ~ `slide-10.webp`: 원본 PPTX에서 렌더링된 배경 이미지
- `.nojekyll`: GitHub Pages 설정

## GitHub Pages 게시
1. ZIP 압축을 풀어 파일과 `assets` 폴더를 저장소 **최상위 경로**에 업로드합니다.
2. GitHub 저장소의 Settings → Pages → Build and deployment → Deploy from a branch 선택.
3. `main` / `/(root)` 지정 후 Save.
4. 제공된 `https://<계정>.github.io/<저장소>/` 링크에 접속합니다.

## 조작
- PC: ← → 화살표, PageUp/PageDown, Home/End, 스페이스
- 모바일: 슬라이드 좌우 스와이프
- 목차/이전·다음/전체 화면/상세 정보 패널 제공
- 카드 및 원본 슬라이드의 주요 영역을 클릭하면 출처와 상세 정보 표시

## 참고
- 모든 이미지·스크립트는 상대 경로로 연결되어 GitHub Pages 하위 경로에서도 작동합니다.
- 제3자 JavaScript 라이브러리, 외부 폰트, 서버, 데이터베이스가 필요 없습니다.
- 브라우저 보안 제한 때문에 `file://`로 직접 여는 경우 `data.json`을 못 읽을 수 있습니다. GitHub Pages에 배포하거나 `python -m http.server 8000`을 실행한 뒤 `http://localhost:8000`에서 보세요.
- 2026년 사업 성과는 원본에 없는 수치를 추가하지 않았습니다. 제안으로 표시된 발전 방향은 확정 사업으로 다루지 않습니다.
