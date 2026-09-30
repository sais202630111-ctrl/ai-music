## 프로젝트 개요

피그마 **ai-music** 디자인을 기반으로  
**AI 음악 추천 챗봇**과 **관리자(CRUD) 페이지**를 웹으로 구현했습니다.

Figma: [ai-music](https://www.figma.com/design/OwnElGrsMeSasNnUz5kcwO/ai-music)

---

## 구현 내용

| 파일 | 설명 |
|------|------|
| `index.html` / `app.js` | AI 음악 추천 챗봇 UI (모바일 프레임) |
| `admin.html` / `admin.js` | 음악 데이터 관리 (검색 · 필터 · 추가 · 삭제) |
| `styles.css` | 다크 테마 + 라임(`#e2ff00`) 액센트 디자인 |
| `README.md` | 프로젝트 소개 및 실행 방법 |
| `REPORT.md` | 깃허브 업로드 과정 및 기술적 어려움 보고서 |

---

## 주요 기능

### 챗봇 (`index.html`)
- 사용자 / AI 메시지 버블
- 추천 곡 카드 (별점 · 코멘트 · 관리 목록 · 미리듣기)
- 입력창으로 추가 추천 요청

### 관리자 (`admin.html`)
- 사이드바 메뉴
- 곡 목록 테이블 (검색, 장르 필터, 정렬)
- 새 곡 추가 모달
- 행 삭제 및 체크박스 선택

---

## 데이터

추천 곡은 **2026년 8월 멜론 월간 차트** 기준으로 반영했습니다.

- LOVE ATTACK — RESCENE  
- 갑자기 — I.O.I  
- REDRED — CORTIS  
- LEMONADE — aespa  
- Pretty Girl — RESCENE  
- 외 다수

---

## 실행 방법

```bash
# index.html 또는 admin.html을 브라우저에서 열기
open index.html


---
**Commit message**에는 짧게 이렇게 넣으면 됩니다.
