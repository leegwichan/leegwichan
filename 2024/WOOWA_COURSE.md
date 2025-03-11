# 우아한테크코스 6기 웹 백엔드 과정

### 교육 기간

- 2024년 2월 ~ 11월 (10개월)

## 우아한테크코스 소개

### 교육 목표

- 현업 1년에 준하는 개발자
- 프로세스를 지키면서 프로젝트를 진행하고, 협업 경험을 가진 개발자
- 자기 주도적 학습하며 지속적으로 성장하는 개발자

### 교육 철학

- 많은 지식을 전달하기 보다 **효과적으로 학습하는 습관을 만드는데 집중**한다
- 교육 기간만 학습하기 보다 **평생 학습할 수 있는 기반을 만드는데 집중**한다
- 혼자 학습하기 보다 **함께 학습하는 것의 즐거움을 느끼도록 만드는데 집중**한다

### 핵심 교육 방식

- **미션기반의 코드 리뷰 중심**
  - 강의식 수업보다는 단계별로 나누어져 있는 여러 개의 미션을 통해 학습합니다. 미션을 구현한 후 현장 경험을 가진 경력 개발자에게 리뷰 요청을 하면 피드백을 받는 방식으로 진행합니다.
- **소통과 협업 위주 학습**
  - 모든 미션 진행을 짝 프로그래밍으로 진행하여 교육생 사이에 토론을 활성화하고, 공동 학습 환경을 구축합니다.
- **현장 중심 교육**
  - 교육 과정의 절반을 프로젝트로 구성하여 현장과 같은 협업 경험을 하고, 레거시 코드를 리팩터링 하는 경험을 하도록 설계합니다.

## 웹 백엔드 교육 과정

## Level 1

### 학습 목표

- 자바 프로그래밍 언어에 대한 핵심 개념을 익혀 프로그래밍하는 경험을 한다.
- 읽기 좋은 코드를 구현하는 것이 왜 중요한지와 코드를 개선해 읽기 좋은 코드로 변경해 보는 경험을 한다.
- 자신이 구현한 코드에 대해 단위 테스트와 리팩토링하는 경험을 한다.
- 데이터베이스를 활용한 콘솔 애플리케이션을 개발하는 경험을 한다.

### 미션 진행 방식

- 한 Step 마다 주어진 요구사항에 맞추어 구현한다.
  - Step1은 페어 프로그래밍으로 진행하며 Step2는 혼자 진행한다.
- 각 Step 의 구현이 완료 후 '리뷰 요청 -> 코드 리뷰 -> 리뷰 반영'의 과정을 반복한다.
  - 리뷰는 현업 개발자에게 각 미션 별 요구사항과 학습 목표를 달성했는지 확인받는다.
  - 리뷰어가 요구사항과 학습 목표가 지켜졌다고 판단하면, 다음 Step 으로 넘어간다.

### 미션 목록

| Mission | Keyword                   | Code                                                           | PR & Reviews                                                                                                                                |
|---------|---------------------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| 자동차 경주  | 단위 테스트                    | [java-racingcar](https://github.com/leegwichan/java-racingcar) | Step1: [PR](https://github.com/woowacourse/java-racingcar/pull/656)<br/>Step2: [PR](https://github.com/woowacourse/java-racingcar/pull/737) |
| 사다리 타기  | TDD, 리팩터링                 | [java-ladder](https://github.com/leegwichan/java-ladder)       | Step1: [PR](https://github.com/woowacourse/java-ladder/pull/259)<br/>Step2: [PR](https://github.com/woowacourse/java-ladder/pull/372)       |
| 블랙잭     | 람다, 스트림<br/>상속과 조합, 불변 객체 | [java-blackjack](https://github.com/leegwichan/java-blackjack) | Step1: [PR](https://github.com/woowacourse/java-blackjack/pull/622)<br/>Step2: [PR](https://github.com/woowacourse/java-blackjack/pull/711) |
| 체스      | OOP<br/>데이터베이스, JDBC      | [java-chess](https://github.com/leegwichan/java-chess)         | Step1: [PR](https://github.com/woowacourse/java-chess/pull/672)<br/>Step2: [PR](https://github.com/woowacourse/java-chess/pull/806)         |

## Level 2

### 학습 목표

- 웹 애플리케이션을 개발하며 웹 백엔드 개발자의 기본 역량을 쌓는다.
  - 주어진 요구사항에 맞춰 기능을 추가/변경하며 애플리케이션을 발전시켜 나간다.
  - 클라우드 환경에 배포를 하여 사용자에게 서비스할 수 있는 최소한의 상태로 만든다.
- 웹 애플리케이션 구현을 위해 필요한 새로운 기술을 학습한다.
  - 이 과정에서 효과적으로 새로운 기술을 익힐 수 있는 본인만의 학습 방법을 찾는 시도를 한다.
- 웹 프로그래밍 과정에서도 **읽기 좋은 코드, 유지보수하기 좋은 코드**를 작성하는 경험을 한다.

### 미션 진행 방식

- 한 Step 마다 주어진 요구사항에 맞추어 구현한다.
  - Step1은 페어 프로그래밍으로 진행하며 Step2는 혼자 진행한다.
- 각 Step 의 구현이 완료 후 '리뷰 요청 -> 코드 리뷰 -> 리뷰 반영'의 과정을 반복한다.
  - 리뷰는 현업 개발자에게 각 미션 별 요구사항과 학습 목표를 달성했는지 확인받는다.
  - 리뷰어가 요구사항과 학습 목표가 지켜졌다고 판단하면, 다음 Step 으로 넘어간다.
- Level 1과 달리 각 미션들은 이전 미션들에서 기능이 추가되어가며, 하나의 서비스를 점진적으로 발전시켜나가는 과정을 경험한다.

### 미션 목록

| Mission     | Keyword                             | Code                                                                                 | PR & Reviews                                                                                                                                                     |
|-------------|-------------------------------------|--------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 방탈출 예약 관리   | 기본 웹 요청 처리<br/>레이어드 아키텍쳐            | [spring-roomescape-admin](https://github.com/leegwichan/spring-roomescape-admin)     | Step1: [PR](https://github.com/woowacourse/spring-roomescape-admin/pull/45)<br/>Step2: [PR](https://github.com/woowacourse/spring-roomescape-admin/pull/91)      |
| 방탈출 사용자 예약  | HTTP & API 설계<br/>사용자 인증<br/>통합 테스트 | [spring-roomescape-member](https://github.com/leegwichan/spring-roomescape-member)   | Step1: [PR](https://github.com/woowacourse/spring-roomescape-member/pull/45)<br/>Step2: [PR](https://github.com/woowacourse/spring-roomescape-member/pull/122)   |
| 방탈출 예약 대기   | JPA로 전환하기<br/>Spring에서 단위 테스트       | [spring-roomescape-waiting](https://github.com/leegwichan/spring-roomescape-waiting) | Step1: [PR](https://github.com/woowacourse/spring-roomescape-waiting/pull/41)<br/>Step2: [PR](https://github.com/woowacourse/spring-roomescape-waiting/pull/123) |
| 방탈출 결제 / 배포 | 외부 API 연동<br/>신규 도메인 추가 & 설계        | [spring-roomescape-payment](https://github.com/leegwichan/spring-roomescape-payment) | Step1: [PR](https://github.com/woowacourse/spring-roomescape-payment/pull/5)<br/>Step2: [PR](https://github.com/woowacourse/spring-roomescape-payment/pull/137)  |

## Level 3

### 학습 목표

- 개발 프로세스 기반으로 프로젝트를 진행, 협업한다.
- 서비스를 기획, 구현, 배포해 실사용자가 사용하도록 개발한다.

### 진행 방식

- 스프린트는 2주 단위로 진행되며, 각 스프린트는 **프로젝트 진행**을 위한 요구사항이 존재한다.
- 각 요구사항이 지켜졌는지 확인할 수 있는 문서를 제출하고, 코치에게 이에 대한 피드백을 받는다.

### 프로젝트

- 땅콩 : 심심풀이 땅콩처럼 가벼운 주제로 친구들과 즐기는 단체 대화주제 제공 서비스
  - [Repository](https://github.com/woowacourse-teams/2024-ddangkong)
  - [PR 목록](https://github.com/woowacourse-teams/2024-ddangkong/pulls?q=is%3Apr+author%3Aleegwichan)
  - [서비스 URL](https://ddangkong.kr)

## Level 4

### 학습 목표

- 팀 프로젝트로 진행한 결과물을 유지 보수하며 서비스를 운영하는 경험을 한다.
  - 레거시 코드를 점진적으로 리팩터링하고 애플리케이션 설계 역량을 높인다.
  - 대용량 서비스를 위한 시스템 아키텍처 설계, 데이터 처리 경험을 한다.
- 웹 백엔드 개발자가 알아야할 최소한의 지식을 미션을 통해 학습한다.
  - 웹 서버의 일부분를 직접 구현하여 HTTP에 대한 이해도를 높인다.
  - 나만의 라이브러리를 직접 구현하여 업무에서 발생하는 중복 코드를 제거하는 역량을 쌓는다.
  - MVC, DI 컨테이너, AOP를 직접 구현하여 스프링 프레임워크의 내부 동작 원리에 대한 이해도를 높인다.
  - 웹 서버, 라이브러리, 프레임워크를 구현하면서 TDD, 클린 코드, 객체지향설계에 대한 연습을 한다.

### 프로젝트 유지 보수

- 스프린트는 4주 단위로 진행되며, 각 스프린트는 **서비스가 성장하는 상황을 연습**하기 위한 요구사항이 존재한다.
- 각 요구사항이 지켜졌는지 확인할 수 있는 문서를 제출하고, 코치에게 이에 대한 피드백을 받는다.

### 미션

#### 진행 방식

- 한 Step 마다 주어진 요구사항에 맞추어 구현한다.
  - 각 Step은 혼자 진행한다.
- 각 Step 의 구현이 완료 후 '리뷰 요청 -> 코드 리뷰 -> 리뷰 반영'의 과정을 반복한다.
  - 리뷰는 동료에게 각 미션 별 요구사항과 학습 목표를 달성했는지 확인받는다.
  - 리뷰어가 요구사항과 학습 목표가 지켜졌다고 판단하면, 다음 Step 으로 넘어간다.

#### 미션 목록

| Mission         | Keyword                 | Code                                                     | PR & Reviews                                                                                                                                                                                                                                                            |
|-----------------|-------------------------|----------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Tomcat 구현하기     | HTTP, 서블릿<br/>스레드, 스레드풀 | [java-http](https://github.com/leegwichan/java-http)     | Step1: [PR](https://github.com/woowacourse/java-http/pull/507)<br/>Step2: [PR](https://github.com/woowacourse/java-http/pull/600)<br/>Step3: [PR](https://github.com/woowacourse/java-http/pull/666)<br/>Step4: [PR](https://github.com/woowacourse/java-http/pull/709) |
| @MVC 구현하기       | Spring MVC 구조           | [java-mvc](https://github.com/leegwichan/java-mvc)       | Step1: [PR](https://github.com/woowacourse/java-mvc/pull/647)<br/>Step2: [PR](https://github.com/woowacourse/java-mvc/pull/722)<br/>Step3: [PR](https://github.com/woowacourse/java-mvc/pull/778)                                                                       |
| JDBC 라이브러리 구현하기 | JDBC 라이브러리<br/>트랜젝션     | [java-jdbc](https://github.com/leegwichan/java-jdbc)     | Step1: [PR](https://github.com/woowacourse/java-jdbc/pull/665)<br/>Step2: [PR](https://github.com/woowacourse/java-jdbc/pull/749)<br/>Step3: [PR](https://github.com/woowacourse/java-jdbc/pull/779)<br/>Step4: [PR](https://github.com/woowacourse/java-jdbc/pull/869) |
| DB 복제와 캐시       | 복제 지연<br/>캐시            | [java-coupon](https://github.com/leegwichan/java-coupon) | Step1: [PR](https://github.com/woowacourse/java-coupon/pull/37)<br/>Step2: [PR](https://github.com/woowacourse/java-coupon/pull/105)                                                                                                                                    |
