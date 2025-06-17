# ☁️ 연락처 관리 웹 프로젝트 (Contact Manager)

간단한 UI/UX 설계와 JavaScript 기반의 클라이언트 사이드 저장 기능을 통해  
**연락처 추가, 수정, 삭제, 필터링**이 가능한 웹 앱을 구현하였습니다.


## 🧩 프로젝트 개요

- **주제**: 클라우드 기반 연락처 관리 웹 페이지 개발
- **주요 기능**: 연락처 CRUD, 태그 분류, 동적 UI
- **사용 기술**: HTML, CSS, JavaScript, JSON (Fetch API), Figma


## 🖌️ UI 설계 (Figma)

초기 UI/UX는 Figma를 이용하여 구성하였습니다.

<img src="https://github.com/user-attachments/assets/a1563449-bf9b-4bd6-9d1d-c0c0be723e56" width="500"/>

## 🖥️ 메인 페이지

- 전체 연락처 목록 표시
- 상단의 `+` 버튼 클릭 시, 연락처 추가 화면으로 이동
- "전체" 버튼 클릭 시 태그 분류 메뉴 표시

<img src="https://github.com/user-attachments/assets/3e544b8c-469f-4b3e-93d3-83dd7918677d" width="500"/>



## ➕ 연락처 추가 기능

- 이름, 전화번호, 이메일, 태그 입력 후 저장
- 저장된 연락처는 메인 페이지에 바로 반영됨

<img src="https://github.com/user-attachments/assets/9154a573-0351-4688-a6ca-3a610736fb67" width="500"/>



## ✏️ 연락처 수정 및 삭제

- 연락처 클릭 시 상세 보기 및 수정/삭제 가능
- 수정 후 체크 버튼 → 저장 / 휴지통 버튼 → 삭제

| 수정 전 | 수정 후 |
|---------------|----------|
| <img src="https://github.com/user-attachments/assets/f9bb3e24-42d9-454c-91c9-f23e904e86cf" width="350"/> | <img src="https://github.com/user-attachments/assets/68abe7ee-375e-45c3-973c-4e7a4fe403de" width="350"/> |


| 삭제 |
|---------------|
| <img src="https://github.com/user-attachments/assets/b6717258-6e82-4be9-b270-39daf2ac5495" width="350"/> | 



## 🧠 핵심 기술

- **UI 설계**: Figma로 사용자 중심 시안 제작
- **동적 목록 처리**: JS로 동적 렌더링 및 JSON 처리
- **태그 분류 기능**: 필터링 로직 구현
- **상태 저장**: 서버 없이 JSON 파일을 통한 fetch 로직 구성


## 🛠️ 기술 스택

| 구분       | 내용                         |
|------------|------------------------------|
| Language   | HTML, CSS, JavaScript        |
| Tool       | Figma, GitHub                |
| Data Logic | JSON 파일 기반 CRUD 처리     |
| 구조       | index.html / main.html / sub.html 파일 분리 구조 |

---

## 📌 회고 및 발전 방향

- 간단한 구조의 CRUD 웹 구현을 통해 프론트엔드 UI 흐름에 대한 감을 익힘
- 추후에는 **Spring Boot + DB 연동**을 통해 서버 저장 방식으로 고도화할 예정
