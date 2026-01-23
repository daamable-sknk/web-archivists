# 프로젝트 문서

이 디렉토리에는 "아키비스트는 웹을 꿈꾸는가" 프로젝트의 기획 및 개발 문서가 포함되어 있습니다.

## 문서 목록

| 파일 | 설명 |
|------|------|
| [start.md](./start.md) | 원본 기획 문서 (교육 개요, 커리큘럼, 참고 자료) |
| [project-plan.md](./project-plan.md) | 웹사이트 개발 계획 및 작업 목록 |
| [design-spec.md](./design-spec.md) | 디자인 명세 및 스타일 가이드 |
| [content.md](./content.md) | 웹사이트 콘텐츠 (텍스트) |
| [progress.md](./progress.md) | 개발 진행 내역 및 버전 히스토리 |

## 프로젝트 구조

```
web-archivists/
├── index.html          # 메인 페이지 (현재: 원페이지 대시보드 레이아웃)
├── index-v1.html       # 백업: 첫 번째 버전
├── index-v2.html       # 백업: 두 번째 버전 (세로 스크롤)
├── curriculum/
│   └── index.html      # 커리큘럼 페이지
├── css/
│   ├── style.css       # 공통 스타일 (현재 버전)
│   ├── style-v1.css    # 백업: 첫 번째 버전
│   └── style-v2.css    # 백업: 두 번째 버전
├── assets/
│   ├── favicon.ico     # 파비콘 (예정)
│   └── og-image.png    # Open Graph 이미지 (예정)
└── docs/               # 문서
    ├── README.md       # 이 파일
    ├── start.md        # 원본 기획
    ├── project-plan.md # 개발 계획
    ├── design-spec.md  # 디자인 명세
    ├── content.md      # 콘텐츠
    └── progress.md     # 개발 진행 내역
```
