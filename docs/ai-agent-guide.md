# AI Agent Guide

## 프로젝트 개요

- **프로젝트명:** 아키비스트는 웹을 꿈꾸는가
- **목적:** 아키비스트를 위한 웹 리터러시 교육 프로그램 웹사이트
- **기술 스택:** 순수 HTML + CSS (프레임워크 없음, JavaScript 최소화)
- **도메인:** https://web-archivists.xyz/
- **배포:** Netlify

## 주요 파일

```
index.html          # 메인 페이지
curriculum/index.html  # 커리큘럼 페이지 (신청자 전용)
css/style.css       # 전체 스타일시트
assets/             # favicon, og-image
docs/               # 프로젝트 문서
```

## 코딩 컨벤션

### HTML
- 시맨틱 태그 사용 (`<aside>`, `<main>`, `<section>`, `<nav>`)
- 외부 링크: `target="_blank" rel="noopener noreferrer"` 필수
- 외부 링크 텍스트 끝에 ↬ 표시

### CSS
- BEM 스타일 클래스명 (예: `.sidebar-footer`, `.footer-credit`)
- 모노크롬 팔레트: `#000`, `#fff`, `#fafafa`, `#e0e0e0`, `#999999`
- 폰트: Noto Sans KR (Google Fonts)
- 상대 경로 사용 (로컬 파일 열람 가능하도록)

### 주석
- HTML 섹션 구분: `<!-- Section Name -->`
- CSS 섹션 구분: `/* ======== SECTION ======== */`

## 작업 시 주의사항

### 하지 말 것
- JavaScript 추가 (최소화 원칙)
- 새로운 색상 추가 (모노크롬 유지)
- 프레임워크/라이브러리 도입
- 절대 경로 사용

### 유지할 것
- 미니멀한 디자인 톤
- 반응형 레이아웃 (1024px, 640px 브레이크포인트)
- 한글 word-break: `keep-all` 적용
- 기존 클래스 재사용 우선

### 수정 후 확인
- 로컬에서 index.html 직접 열어서 확인 가능
- 모바일/데스크톱 양쪽 레이아웃 점검

## 커밋 전 체크리스트

- [ ] Last updated 날짜 업데이트 (형식: `YYYY.MM.DD`)
  - `index.html` (푸터)
  - `curriculum/index.html` (푸터)
  - `docs/project-plan.md`
  - `docs/ai-agent-guide.md`

## 커밋 컨벤션

```
<type>: <제목>

<본문 설명>
```

### Type
| Type | 설명 |
|------|------|
| `feat` | 새로운 기능 추가 |
| `fix` | 버그 수정 |
| `style` | CSS 스타일 변경, 코드 포맷팅 |
| `docs` | 문서 추가/수정 |
| `refactor` | 코드 리팩토링 (기능 변경 없음) |
| `chore` | 빌드, 설정 파일 등 기타 작업 |

### 작성 규칙
- 제목과 본문 모두 **한국어**로 작성
- 제목은 간결하게, 본문은 친절하고 누구나 알아볼 수 있게
- 무엇을 왜 변경했는지 설명

### 예시
```
feat: 푸터에 마지막 업데이트 날짜 추가

메인 페이지와 커리큘럼 페이지 푸터에 "Last updated: YYYY.MM.DD" 형식의
날짜 표시를 추가했습니다. 방문자가 콘텐츠의 최신 여부를 확인할 수 있습니다.
```

```
fix: 모바일에서 사이드바 넘침 현상 수정

화면 너비 640px 이하에서 사이드바 텍스트가 영역을 벗어나는 문제를
word-break: keep-all 속성을 적용하여 해결했습니다.
```

```
docs: AI 에이전트 가이드 문서 작성

AI 세션 시작 시 프로젝트 맥락을 빠르게 파악할 수 있도록
프로젝트 개요, 코딩 컨벤션, 작업 시 주의사항을 정리한 문서를 추가했습니다.
```

---

Last updated: 2026.01.24
