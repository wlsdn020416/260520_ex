# Java Spring Boot 포트폴리오 프로젝트

취업을 위한 Java Spring Boot 포트폴리오 프로젝트 6개입니다.
각 프로젝트는 실무에서 자주 사용되는 기술 스택과 설계 패턴을 포함하고 있습니다.

---

## 📌 프로젝트 목차

1. [쇼핑몰 시스템 (E-Commerce)](#1-쇼핑몰-시스템-e-commerce)
2. [SNS 애플리케이션](#2-sns-애플리케이션)
3. [실시간 채팅 서비스](#3-실시간-채팅-서비스)
4. [예약 관리 시스템](#4-예약-관리-시스템)
5. [블로그 & 커뮤니티 플랫폼](#5-블로그--커뮤니티-플랫폼)
6. [가계부 & 재무관리 서비스](#6-가계부--재무관리-서비스)

---

## 1. 쇼핑몰 시스템 (E-Commerce)

### 📝 프로젝트 설명
온라인 쇼핑몰 플랫폼으로, 상품 조회, 장바구니, 주문, 결제 등의 전체 전자상거래 기능을 제공합니다.

### 🛠️ 기술 스택
- **Backend**: Spring Boot, Spring Data JPA, Spring Security
- **Database**: MySQL, Redis (캐싱)
- **결제**: PayPal/Stripe API 연동
- **검색**: Elasticsearch
- **메시지 큐**: RabbitMQ (주문 처리)

### ✨ 주요 기능
- 상품 검색 및 필터링 (카테고리, 가격, 평점)
- 장바구니 및 위시리스트 관리
- 주문 및 결제 처리 (다중 결제 방식)
- 배송 추적
- 관리자 대시보드 (상품 관리, 주문 관리, 매출 분석)
- 리뷰 및 평점 시스템
- 쿠폰/할인 코드 적용

### 📊 학습 포인트
- REST API 설계 및 구현
- 트랜잭션 관리 및 동시성 제어
- 결제 게이트웨이 API 통합
- 캐싱 전략 (Redis)
- 데이터베이스 최적화

---

## 2. SNS 애플리케이션

### 📝 프로젝트 설명
소셜 네트워크 서비스로, 사용자 팔로우, 포스트 작성, 댓글, 좋아요 등의 SNS 기능을 제공합니다.

### 🛠️ 기술 스택
- **Backend**: Spring Boot, Spring Data JPA, Spring WebFlux
- **Database**: MySQL, MongoDB (NoSQL)
- **File Storage**: AWS S3, MinIO
- **실시간**: WebSocket
- **검색**: Elasticsearch

### ✨ 주요 기능
- 회원 가입 및 프로필 관리
- 팔로우/언팔로우 시스템
- 포스트 작성, 수정, 삭제
- 이미지/동영상 업로드
- 댓글 및 대댓글 시스템
- 좋아요 기능 (포스트, 댓글)
- 피드 생성 및 추천 알고리즘
- 해시태그 및 검색
- 알림 시스템

### 📊 학습 포인트
- 관계형 데이터베이스 설계 (정규화)
- NoSQL 활용
- 파일 업로드 처리 및 스토리지 연동
- 피드 알고리즘 구현
- WebSocket을 통한 실시간 알림

---

## 3. 실시간 채팅 서비스

### 📝 프로젝트 설명
1:1 및 그룹 채팅을 지원하는 실시간 메시징 플랫폼입니다.

### 🛠️ 기술 스택
- **Backend**: Spring Boot, Spring WebSocket
- **Database**: MySQL, Redis (메시지 캐싱)
- **Message Queue**: RabbitMQ, Kafka
- **Frontend**: WebSocket, JavaScript
- **API**: REST API

### ✨ 주요 기능
- 1:1 실시간 채팅
- 그룹 채팅
- 채팅 히스토리 조회
- 파일 및 이미지 공유
- 읽음 표시 (Read Receipt)
- 타이핑 표시 (Typing Indicator)
- 채팅방 즐겨찾기
- 사용자 온라인 상태 표시

### 📊 학습 포인트
- WebSocket 프로토콜 이해 및 구현
- 메시지 큐 기반 아키텍처
- 동시성 처리 및 세션 관리
- Redis를 활용한 캐싱 전략
- 확장 가능한 채팅 아키텍처 설계

---

## 4. 예약 관리 시스템

### 📝 프로젝트 설명
카페, 병원, 미용실 등 다양한 서비스의 예약을 관리할 수 있는 플랫폼입니다.

### 🛠️ 기술 스택
- **Backend**: Spring Boot, Spring Data JPA
- **Database**: MySQL
- **Scheduler**: Quartz, Spring Scheduler
- **Email**: JavaMailSender, SendGrid
- **SMS**: Twilio API

### ✨ 주요 기능
- 예약 생성, 수정, 취소
- 시간대별 가능 시간 조회
- 중복 예약 방지
- 자동 리마인더 (Email, SMS)
- 예약자 관리 및 이력 조회
- 취소 정책 설정
- 관리자 일정 관리
- 통계 및 분석 (예약률, No-show율)

### 📊 학습 포인트
- 스케줄링 기능 구현
- 외부 API 연동 (Email, SMS)
- 시간대 충돌 감지 알고리즘
- 트랜잭션 격리 수준 이해
- 비즈니스 로직 설계

---

## 5. 블로그 & 커뮤니티 플랫폼

### 📝 프로젝트 설명
사용자가 블로그를 작성하고, 커뮤니티에서 질문/답변을 공유할 수 있는 플랫폼입니다.

### 🛠️ 기술 스택
- **Backend**: Spring Boot, Spring Data JPA
- **Database**: MySQL
- **Text Editor**: Markdown 또는 Rich Text Editor
- **Search**: Elasticsearch
- **Cache**: Redis

### ✨ 주요 기능
- 블로그 포스트 작성, 수정, 삭제 (Markdown 지원)
- 태그 및 카테고리 분류
- 댓글 및 대댓글 시스템
- 좋아요 및 북마크 기능
- 전문가 채택 시스템 (Q&A)
- 사용자 평판 포인트 시스템
- 추천 글 및 인기 글 조회
- 고급 검색 기능
- 구독 및 알림 시스템

### 📊 학습 포인트
- 계층 댓글 구조 설계
- 검색 엔진 통합 (Elasticsearch)
- 점진적 캐싱 전략
- 사용자 평판 시스템 설계
- SEO 최적화

---

## 6. 가계부 & 재무관리 서비스

### 📝 프로젝트 설명
개인의 수입/지출을 관리하고, 재무 목표를 설정하며 분석 리포트를 제공하는 서비스입니다.

### 🛠️ 기술 스택
- **Backend**: Spring Boot, Spring Data JPA
- **Database**: MySQL
- **Chart/Report**: Apache POI, JasperReports
- **Scheduler**: Spring Scheduler
- **Export**: PDF, Excel

### ✨ 주요 기능
- 수입/지출 기록
- 카테고리별 분류 및 통계
- 예산 설정 및 초과 알림
- 목표 저축 관리
- 월별/연도별 리포트
- 자산 추적 (은행, 투자, 현금)
- 정기 거래 자동화
- 다양한 차트 및 시각화
- PDF/Excel 내보내기
- 가족 공유 기능

### 📊 학습 포인트
- 재정 계산 및 로직 구현
- 데이터 분석 및 시각화
- 리포트 생성 (PDF, Excel)
- 대량 데이터 처리 최적화
- 보안 (민감한 금융 데이터 보호)

---

## 🎯 공통 학습 목표

모든 프로젝트에서 다음의 기술과 개념을 적용해야 합니다:

### 백엔드 개발
- ✅ Spring Boot 기초 및 고급 개념
- ✅ Spring Data JPA 및 Hibernate ORM
- ✅ RESTful API 설계 및 구현
- ✅ 스프링 시큐리티 (인증/인가)
- ✅ 예외 처리 및 에러 핸들링
- ✅ 로깅 및 모니터링

### 데이터베이스
- ✅ MySQL 설계 및 최적화
- ✅ 데이터베이스 정규화
- ✅ 인덱싱 및 쿼리 최적화
- ✅ 트랜잭션 관리

### 아키텍처 & 설계
- ✅ MVC 패턴
- ✅ 계층화 아키텍처 (Controller → Service → Repository)
- ✅ 디자인 패턴 (Singleton, Factory, Strategy 등)
- ✅ SOLID 원칙
- ✅ TDD (Test-Driven Development)

### 도구 & 환경
- ✅ Git 및 GitHub
- ✅ Maven 또는 Gradle 빌드 도구
- ✅ Docker 컨테이너화
- ✅ JUnit 및 Mockito 테스트
- ✅ Postman/Insomnia API 테스트
- ✅ Jenkins/GitHub Actions CI/CD

---

## 💡 개발 팁

### 1. 실제 사용 사례 고려
- 각 프로젝트를 완전한 기능으로 구현하기보다는 핵심 기능에 집중
- 사용자 관점에서 생각하고 실무적인 요구사항 적용

### 2. 코드 품질
- 클린 코드 작성 (명확한 네이밍, 적절한 주석)
- 단위 테스트 작성 (최소 70% 커버리지)
- 코드 리뷰 및 리팩토링

### 3. 문서화
- README 작성 (프로젝트 설명, 설치 방법, 사용 방법)
- API 문서 (Swagger/SpringFox)
- DB 스키마 다이어그램
- 프로젝트 아키텍처 설명

### 4. 배포
- Docker로 컨테이너화
- AWS, Azure, 또는 Heroku에 배포
- 배포 과정을 문서화

---

## 📚 추천 학습 자료

- 공식 Spring Boot 문서: https://spring.io/projects/spring-boot
- 인프런 Spring Boot 강의
- 우아한 형제들 기술 블로그
- Java 백엔드 개발자 로드맵

---

## 🚀 시작하기

각 프로젝트별로 다음 단계를 따르세요:

1. **프로젝트 초기 설정**
   ```
   Spring Initializr에서 프로젝트 생성
   필요한 의존성 추가
   ```

2. **데이터베이스 설계**
   ```
   ERD 작성
   테이블 생성 SQL 작성
   ```

3. **백엔드 개발**
   ```
   Entity 클래스 작성
   Repository 인터페이스 생성
   Service 비즈니스 로직 구현
   Controller REST API 구현
   ```

4. **테스트**
   ```
   단위 테스트 작성
   통합 테스트 작성
   ```

5. **배포**
   ```
   Docker 이미지 생성
   클라우드 배포
   ```

---

**마지막 업데이트**: 2026년 5월 20일

**작성자**: Portfolio Developer

---

> 💬 **Tip**: 이 포트폴리오 프로젝트들은 취업 시 강력한 자산이 됩니다.
> 각 프로젝트를 깊이 있게 구현하고, GitHub에 올려두세요!
