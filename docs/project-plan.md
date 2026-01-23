# 웹사이트 개발 계획

## 개요

- **프로젝트명:** 아키비스트는 웹을 꿈꾸는가
- **도메인:** http://web-archivists.xyz/
- **배포:** Netlify
- **GitHub:** https://github.com/daamable-sknk/web-archivists

## 페이지 구성

### 1. 메인 페이지 (`/`)
- 교육 프로그램 소개
- 강의 일정 안내
- 장소 정보
- 신청 버튼 (구글 폼 연결)

### 2. 커리큘럼 페이지 (`/curriculum`)
- 신청 완료자에게만 URL 공유
- 주차별 교육 자료 링크 (구글 프레젠테이션)

## 작업 목록

### Phase 1: 기본 구조 (우선순위 높음)
- [x] 프로젝트 폴더 구조 생성
- [x] docs/ 디렉토리 문서화
- [ ] 메인 페이지 HTML 작성
- [ ] 커리큘럼 페이지 HTML 작성
- [ ] CSS 스타일링

### Phase 2: 에셋 및 연동 (우선순위 중간)
- [ ] favicon 생성
- [ ] Open Graph 이미지 생성
- [x] 구글 폼 생성 및 연결
  - URL: https://docs.google.com/forms/d/e/1FAIpQLScG8Od3blAU0v0j4CyR6j49A5XH1XautJKEvBQADSZG39Al8w/viewform

### Phase 3: 배포 (우선순위 중간)
- [ ] Netlify 배포 설정
- [ ] 도메인 연결 (web-archivists.xyz)

## 구글 폼 필드

1. 이메일 (자동 수집)
2. 이름
3. 자신을 표현할 키워드 5가지
4. 개인정보 수집에 대한 동의 및 안내 (체크박스)

## 참고 링크

- 기획 문서: [start.md](./start.md)
- 레퍼런스 사이트:
  - https://cargo.site/templates
  - https://neworder.xyz/
  - https://birdcall.online/
