# 공부 기록

직접 공부하며 정리한 HTML 학습 자료를 GitHub Pages로 공개하는 저장소입니다.

- 사이트: https://stevenkim18.github.io/learning/

## 구성

| 경로 | 내용 |
| --- | --- |
| `index.html` | 블로그 첫 화면 (전체 목록) |
| `langchain/` | `/learning/langchain/`으로 접속하면 LangChain 목차로 이동 |
| `langchain/ch2/` | LangChain CH 02 · LLM과 LangChain 시작하기 (10개 강의) |

각 강의는 스타일과 스크립트를 파일 안에 포함한 독립 HTML 파일입니다.

## 배포

GitHub 저장소의 **Settings → Pages**에서 `main` 브랜치의 `/ (root)`를 배포 소스로 선택합니다.
`.nojekyll` 파일이 있어 Jekyll 빌드 없이 HTML이 그대로 배포됩니다.
