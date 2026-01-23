# 아키비스트는 웹을 꿈꾸는가

대구예술대학교 방송영상미디어과 교양 수업을 위한 웹 아카이빙 교육 프로젝트입니다.

## 프로젝트 개요

이 프로젝트는 학생들이 웹 아카이빙의 개념과 실습을 통해 디지털 기록 보존의 중요성을 이해하고, 직접 웹사이트를 제작하며 웹 기술의 기초를 배우는 교육 과정을 지원합니다.

## 프로젝트 구조

```
web-archivists/
├── index.html          # 메인 페이지
├── curriculum/
│   └── index.html      # 커리큘럼 페이지
├── css/
│   └── style.css       # 스타일시트
├── assets/
│   ├── favicon.ico     # 파비콘
│   └── og-image.png    # Open Graph 이미지
└── docs/               # 프로젝트 문서
    ├── README.md       # 문서 인덱스
    ├── start.md        # 원본 기획 문서
    ├── project-plan.md # 웹사이트 개발 계획
    ├── design-spec.md  # 디자인 명세 및 스타일 가이드
    ├── content.md      # 웹사이트 콘텐츠
    └── progress.md     # 개발 진행 내역 및 버전 히스토리
```

## 문서

상세한 프로젝트 문서는 [docs](./docs/) 디렉토리를 참고하세요.

| 파일 | 설명 |
|------|------|
| [project-plan.md](./docs/project-plan.md) | 웹사이트 개발 계획 및 작업 목록 |
| [design-spec.md](./docs/design-spec.md) | 디자인 명세 및 스타일 가이드 |
| [content.md](./docs/content.md) | 웹사이트 콘텐츠 (텍스트) |
| [progress.md](./docs/progress.md) | 개발 진행 내역 및 버전 히스토리 |

## 로컬 실행

이 프로젝트는 정적 웹사이트이므로 별도의 빌드 과정 없이 바로 실행할 수 있습니다.

```bash
# 간단한 HTTP 서버 실행 (Python 3)
python3 -m http.server 8000

# 또는 Node.js http-server 사용
npx http-server
```

브라우저에서 `http://localhost:8000`으로 접속하세요.
