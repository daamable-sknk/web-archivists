# 웹사이트 개발 계획

## 개요

- **프로젝트명:** 아키비스트는 웹을 꿈꾸는가
- **도메인:** https://web-archivists.xyz/
- **배포:** Netlify
- **GitHub:** https://github.com/daamable-sknk/web-archivists
- **기술 스택:** HTML + CSS (프레임워크 없음, JavaScript 최소화)

## 페이지 구성

### 1. 메인 페이지 (`/`)
- 원페이지 대시보드 레이아웃 (좌우 분할)
- 왼쪽 사이드바: 교육 정보 (일정/대상/목표/준비물/장소/파트너십/신청)
- 오른쪽 메인: 프로그램 소개, 4주 커리큘럼 카드

### 2. 커리큘럼 페이지 (`/curriculum`)
- 신청 완료자에게만 URL 공유
- 주차별 교육 자료 링크 (Google Presentation)
- 총 9개 프레젠테이션 (보기 전용 모드)

## 작업 진행 상황

### Phase 1: 기본 구조 ✅
- [x] 프로젝트 폴더 구조 생성
- [x] docs/ 디렉토리 문서화
- [x] 메인 페이지 HTML 작성 (원페이지 레이아웃)
- [x] 커리큘럼 페이지 HTML 작성 (Google Presentation 링크 연결)
- [x] CSS 스타일링 (모노크롬, 미니멀 디자인)

### Phase 2: 에셋 및 연동
- [x] favicon 생성
- [x] Open Graph 이미지 생성
- [x] 구글 폼 생성 및 연결
  - URL: https://docs.google.com/forms/d/e/1FAIpQLScG8Od3blAU0v0j4CyR6j49A5XH1XautJKEvBQADSZG39Al8w/viewform

### Phase 3: 배포 ✅
- [x] Netlify 배포 설정
- [x] 도메인 연결 (web-archivists.xyz)

## 구글 폼 필드

1. 이메일 (자동 수집)
2. 이름
3. 자신을 표현할 키워드 5가지
4. 개인정보 수집에 대한 동의 및 안내 (체크박스)

## 현재 레이아웃

### 메인 페이지 특징
- **좌측 사이드바 (400px 고정)**
  - 사이트 타이틀 + 영문 부제
  - 정보 섹션 (일정/대상/목표/준비물/장소/파트너십)
  - 신청 버튼 (신청 기간 전/중/후 상태 전환 가능)
  - 푸터 크레딧

- **우측 메인 콘텐츠**
  - 인트로 섹션 (질문 2개 + 프로그램 소개)
  - 4주 커리큘럼 카드 (호버 효과)

### 커리큘럼 페이지 구조
- Week 01: 5개 프레젠테이션
- Week 02: 3개 프레젠테이션
- Week 03: 2개 프레젠테이션
- Week 04: 1개 프레젠테이션

## 디자인 레퍼런스

- **메인 레퍼런스:** [Cargo Template #3187535](https://cargo.site/templates/preview/3187535)
- **추가 레퍼런스:**
  - https://neworder.xyz/ (텍스트 중심 레이아웃)
  - https://birdcall.online/ (외부링크 화살표 ↬)

## 파트너십

- **한국기록전문가협회** (https://www.archivists.or.kr/)
- **SKUNKWORKS STUDIO** (https://skunkworks.co.kr/)

## 주요 기술 결정

- 순수 HTML/CSS (프레임워크 없음)
- 상대 경로 사용 (로컬 파일 열람 가능)
- 반응형 디자인 (모바일/태블릿/데스크톱)
- 외부 링크에 ↬ 표시
- 모노크롬 컬러 팔레트 (#000, #fff, #fafafa, #e0e0e0)

## 도구

- **AI 코딩 에이전트:** [OpenCode](https://opencode.ai/)와 함께 개발
- **Favicon:** [favicon.io](https://favicon.io/)에서 생성

---

Last updated: 2026.01.24
