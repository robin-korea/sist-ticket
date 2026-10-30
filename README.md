# 🎫 SIST TICKET
> **React와 Spring Boot를 활용한 티켓 예매 및 리뷰 관리 풀스택 웹 서비스**
> 
> 개발 기간: 2026.10.12 ~ 2026.10.23

## 🛠 기술 스택
- **Backend:** Java, Spring Boot, Spring Security, Spring Data JPA
- **Frontend:** React, React Router, HTML/CSS, JavaScript
- **Database:** MySQL
- **Infra:** AWS S3, GitHub

## 🌟 주요 기능 및 아키텍처
SIST TICKET은 클라이언트와 서버가 완전히 분리된 환경에서 동작하며, 프론트엔드와 백엔드의 유기적인 통신을 통해 다음과 같은 핵심 기능을 제공합니다.

- **안전한 권한 검증 및 세션 유지:** 비동기 통신 시 `credentials` 제어 및 Spring Security 기반 API 이중 권한 검증
- **데이터 무결성 확보:** 회원 탈퇴 시 물리적 삭제 대신 논리적 삭제(Soft Delete)를 적용하여 서비스 운영 데이터 보존
- **파일 비동기 처리:** `FormData`를 활용해 텍스트와 멀티파트(이미지) 파일을 통합 전송하고 AWS S3에 적재
- **프론트엔드 최적화:** 쿼리 파라미터를 활용한 단일 인증 컴포넌트 재사용 및 동적 라우팅 구현

## 👨‍💻 나의 역할 (안정빈)
**마이페이지 및 리뷰 시스템 풀스택 개발 (Front/Back)**
- 회원 정보 수정 및 탈퇴 로직 구현 (Soft Delete 적용)
- 사용자 리뷰 작성(이미지 S3 업로드) 및 관리자 전용 리뷰 제어 시스템 구축
- React 쿼리 파라미터를 활용한 동적 라우팅 및 컴포넌트 재사용 설계

---
※ 프론트엔드와 백엔드의 상세한 실행 방법 및 코드는 아래 폴더에서 확인하실 수 있습니다.
- [👉 Frontend 상세 코드 및 설명 보기](./frontend)
- [👉 Backend 상세 코드 및 설명 보기](./backend)
