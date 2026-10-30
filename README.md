# ROBROS Portfolio

ROBROS 지원용 신동찬 포트폴리오의 독립 프로젝트입니다.

배포 주소: https://alpha8332.github.io/portfolio-robros/

이 저장소 루트의 HTML과 assets를 직접 수정하고 main 브랜치에 반영합니다. GitHub Pages는 main 브랜치의 루트에서 배포합니다.

## 로컬 확인

이 폴더에서 `python -m http.server 4318`을 실행하고 `http://127.0.0.1:4318/index.html`을 엽니다. 파일을 직접 여는 경우에도 `index.html`을 사용합니다.

## 텍스트 내보내기

본문을 수정한 뒤 `python scripts/export-public-text.py`를 실행해 portfolio.md를 갱신합니다.
