# JPASHOP

## 프로젝트 소개
Spring Boot와 JPA를 활용하여  
**도메인 모델 중심으로 설계한 쇼핑몰 예제 프로젝트**입니다.

김영한님의 JPA 로드맵(JPA1 → JPA2)을 따라가며  
기본 기능 구현 이후 점진적인 리팩토링과 성능 개선을 진행합니다.

---

## 학습 목표
- JPA 엔티티 설계 및 연관관계 매핑 이해
- 트랜잭션과 변경 감지(Dirty Checking) 동작 원리 학습
- 서비스 / 리포지토리 책임 분리
- JPQL을 활용한 조회 기능 구현
- 리팩토링을 통한 코드 품질 개선

---

## 기술 스택
- Java 17
- Spring Boot
- JPA (Hibernate)
- Gradle
- H2 Database
- Thymeleaf

---

## 프로젝트 구조
- domain: 엔티티 및 핵심 비즈니스 로직
- service: 트랜잭션 경계 및 도메인 조합
- repository: JPA 기반 데이터 접근
- controller: 웹 요청 처리

---

## 진행 단계
- JPA1: 기본 도메인 모델 및 CRUD 구현
- JPA2: 성능 최적화 및 조회 개선 (예정)

