# HTML/CSS 실습 프로젝트

신형철 평론가 인터뷰 기사를 활용한 HTML/CSS 단계별 실습입니다.

## 파일 구성

| 파일 | 설명 |
|------|------|
| `00-plain.txt` | 원본 텍스트 |
| `01-plain.html` | 평문 그대로 HTML에 넣기 (마크업 없음) |
| `02-structure.html` | 시맨틱 HTML로 구조화 (CSS 없음) |
| `03-styled.html` | CSS 스타일 적용 |
| `03-styled.css` | 스타일시트 |
| `images/` | 이미지 폴더 |

## 실습 단계

### 1단계: 평문 (`01-plain.html`)
- HTML 태그 없이 텍스트만 `<body>`에 넣은 상태
- 브라우저가 어떻게 렌더링하는지 확인
- **학습 포인트**: 마크업 없이는 구조가 없다

### 2단계: HTML 구조 (`02-structure.html`)
- 시맨틱 태그로 콘텐츠 구조화
- 사용 태그: `<header>`, `<main>`, `<section>`, `<h1>`~`<h2>`, `<p>`, `<blockquote>`, `<figure>`, `<aside>`, `<footer>`
- **학습 포인트**: 브라우저 기본 스타일, 시맨틱 마크업의 의미

### 3단계: CSS 스타일 (`03-styled.html`)
- `03-styled.css` 연결
- 적용된 스타일:
  - 배경색 (`background-color`)
  - 문단 너비 (`max-width`)
  - 이미지 크기 (`width`, `max-width`)
  - 타이포그래피 (폰트, 줄간격)
  - 인용문 스타일 (`blockquote`)
  - 여백/간격 (`margin`, `padding`)

## 실습 방법

1. 각 HTML 파일을 브라우저에서 열어 비교
2. 개발자 도구(F12)로 요소 검사
3. CSS 값을 변경하며 결과 확인

## 출처

대학신문 - 신형철 평론가 인터뷰 (2022)
