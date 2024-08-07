# inflearn-advanced
## 섹션 1. 예제 만들기
- 프로젝트 생성
- 예제 프로젝트 만들기 - V0
- 로그 추적기 - 요구사항 분석
- 로그 추적기 V1 - 프로토타입 개발
- 로그 추적기 V1 - 적용
- 로그 추적기 V2 - 파라미터로 동기화 개발
- 로그 추적기 V2 - 적용

## 섹션 2. 쓰레드 로컬 - ThreadLocal
- 필드 동기화 - 개발
- 필드 동기화 - 적용
- 필드 동기화 - 동시성 문제
- 동시성 문제 - 예제 코드
- ThreadLocal - 소개
- ThreadLocal - 예제 코드
- 쓰레드 로컬 동기화 - 개발
- 쓰레드 로컬 동기화 - 적용
- 쓰레드 로컬 - 주의사항

## 섹션 3. 템플릿 메서드 패턴과 콜백 패턴
- 템플릿 메서드 패턴 - 시작
- 템플릿 메서드 패턴 - 예제1
- 템플릿 메서드 패턴 - 예제2
- 템플릿 메서드 패턴 - 예제3
- 템플릿 메서드 패턴 - 적용1
- 템플릿 메서드 패턴 - 적용2
- 템플릿 메서드 패턴 - 정의
- 전략 패턴 - 시작
- 전략 패턴 - 예제1
- 전략 패턴 - 예제2
- 전략 패턴 - 예제3
- 템플릿 콜백 패턴 - 시작
- 템플릿 콜백 패턴 - 예제
- 템플릿 콜백 패턴 - 적용

## 섹션 4. 프록시 패턴과 데코레이터 패턴
- 프로젝트 생성
- 예제 프로젝트 만들기 v1
- 예제 프로젝트 만들기 v2
- 예제 프로젝트 만들기 v3
- 요구사항 추가
- 프록시, 프록시 패턴, 데코레이터 패턴 - 소개
- 프록시 패턴 - 예제 코드1
- 프록시 패턴 - 예제 코드2
- 데코레이터 패턴 - 예제 코드1
- 데코레이터 패턴 - 예제 코드2
- 데코레이터 패턴 - 예제 코드3
- 프록시 패턴과 데코레이터 패턴 정리
- 인터페이스 기반 프록시 - 적용
- 구체 클래스 기반 프록시 - 예제1
- 구체 클래스 기반 프록시 - 예제2
- 구체 클래스 기반 프록시 - 적용
- 인터페이스 기반 프록시와 클래스 기반 프록시

## 섹션 5. 동적 프록시 기술
- 리플렉션
- JDK 동적 프록시 - 소개
- JDK 동적 프록시 - 예제 코드
- JDK 동적 프록시 - 적용1
- JDK 동적 프록시 - 적용2
- CGLIB - 소개
- CGLIB - 예제 코드

## 섹션 6. 스프링이 지원하는 프록시
- 프록시 팩토리 - 소개
- 프록시 팩토리 - 예제 코드1
- 프록시 팩토리 - 예제 코드2
- 포인트컷, 어드바이스, 어드바이저 - 소개
- 예제 코드1 - 어드바이저
- 예제 코드2 - 직접 만든 포인트컷
- 예제 코드3 - 스프링이 제공하는 포인트컷
- 예제 코드4 - 여러 어드바이저 함께 적용
- 프록시 팩토리 - 적용1
- 프록시 팩토리 - 적용2

## 섹션 7. 빈 후처리기
- 빈 후처리기 - 소개
- 빈 후처리기 - 예제 코드1
- 빈 후처리기 - 예제 코드2
- 빈 후처리기 - 적용
- 빈 후처리기 - 정리
- 스프링이 제공하는 빈 후처리기1
- 스프링이 제공하는 빈 후처리기2
- 하나의 프록시, 여러 Advisor 적용

## 섹션 8. @Aspect AOP
- @Aspect 프록시 - 적용
- @Aspect 프록시 - 설명

## 섹션 9. 스프링 AOP 개념
- AOP 소개 - 핵심 기능과 부가 기능
- AOP 소개 - 애스펙트
- AOP 적용 방식
- AOP 용어 정리

## 섹션 10. 스프링 AOP 구현
- 프로젝트 생성
- 예제 프로젝트 만들기
- 스프링 AOP 구현1 - 시작
- 스프링 AOP 구현2 - 포인트컷 분리
- 스프링 AOP 구현3 - 어드바이스 추가
- 스프링 AOP 구현4 - 포인트컷 참조 
- 스프링 AOP 구현5 - 어드바이스 순서
- 스프링 AOP 구현6 - 어드바이스 종류

## 섹션 11. 스프링 AOP - 포인트컷
- 포인트컷 지시자
- 예제 만들기
- execution - 1
- execution - 2
- within
- args
- @target, @within
- @annotation, @args
- bean
- 매개변수 전달
- this, target

## 섹션 12. 스프링 AOP - 실전 예제
- 예제 만들기
- 로그 출력 AOP
- 재시도 AOP

## 섹션 13. 스프링 AOP - 실무 주의사항
- 프록시와 내부 호출 - 문제
- 프록시와 내부 호출 - 대안1 자기 자신 주입
- 프록시와 내부 호출 - 대안2 지연 조회
- 프록시와 내부 호출 - 대안3 구조 변경
- 프록시 기술과 한계 - 타입 캐스팅
- 프록시 기술과 한계 - 의존관계 주입
- 프록시 기술과 한계 - CGLIB
- 프록시 기술과 한계 - 스프링의 해결책
