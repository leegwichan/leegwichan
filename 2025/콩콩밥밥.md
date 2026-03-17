# 콩콩밥밥 스터디

## About 콩콩밥밥 스터디

- **미션 기반 학습:** 우아한테크코스의 학습 방식을 차용하여, '요구사항 구현 - PR - 코드 리뷰 - 피드백 반영' 사이클을 거치며 스프링(Spring)을 학습했습니다.
- **유지보수성 중심의 코드 설계:** 단순한 기능 작동을 넘어 클린 코드와 테스트 코드를 적극적으로 고민하며, 변경에 유연하고 관리하기 좋은 소프트웨어를 만드는 데 집중했습니다.
- **코드 리뷰를 통한 주도적 성장:** 주어진 정답을 찾는 방법이 아닌, 리뷰어와 리뷰이의 치열한 코드 리뷰 과정을 통해 기술에 대한 명확한 근거와 자신만의 학습 철학을 확립했습니다.

## 스터디 방식 & 진행 방식

- 스터디 기간 : 25.02.01 ~ 04.12
- 스터디 인원 : 리뷰이 6명, 리뷰어 5명
- 스터디 진행 방식
    - 총 5개의 미션으로 구성
        1. Spring MVC : 웹 요청과 응답을 처리 방법을 배움
        2. Spring JDBC : 데이터베이스 접근을 위한 기술 JDBC를 배움
        3. Spring Core : 스프링의 객체 관리 기능 및 레이어드 아키텍쳐
        4. Spring MVC(인증) : Spring 기반의 인증을 직접 구현
        5. Spring Data JPA : JDBC에서 JPA로 직접 바꿔보면서 JPA의 장단점을 배움
    - 각 미션을 주어진 기간 내 구현하며, 코드 리뷰를 통해 개선해나감

- 미션 진행 방식
    1. 주도적인 미션 구현 및 PR : 리뷰이는 매주 부여되는 Spring 미션을 스스로 분석해 기능을 구현한 뒤, GitHub에 PR(Pull Request)을 제출
    2. 리뷰어와의 코드 리뷰 진행 : PR이 올라오면 배정된 전담 리뷰어가 24시간 이내에 클린 코드, 아키텍처, 객체지향 관점에서 깊이 있는 피드백을 남김
    3. 리뷰 반영 & 재리뷰 : 리뷰어와의 지속적인 기술적 소통을 바탕으로 코드를 리팩토링하며, 자신만의 확고한 개발 기준과 철학을 확립

## Activity (스터디장)

- Spring 백엔드 스터디 기획 및 총괄 운영
    - 사전 조사 진행 : ‘2025 [초록스터디](https://cho-log.github.io/) 밋업’에 참여하여 유사한 스터디들이 어떻게 운영되는지 파악하고 스터디를 기획함
    - **데이터 기반의 스터디 개선** **:** 매주 구글 폼을 통해 미션 소요 시간과 만족도를 트래킹하고, 참여자들의 피드백을 적극 수용하여 다음 주차의 미션 난이도와 일정을 유연하게 조정하며 스터디를 발전시켜 나갔습니다.

- PR 기반 코드 리뷰 프로세스 운영 및 코드 리뷰 진행
    - **스터디 내 클린 코드 기준 제안** : 리뷰어들의 통일감있는 리뷰를 위해 'Indent depth 제한', 'else 지양' 등 체계적인 클린 코드 기준을 도입했습니다.
    - **학습 자료 제작** **:** 일부 자료(ORM, Spring Data JPA)에 대해서는 스터디 맞춤형 자료를 직접 제작하여 공유했습니다.

- **주기적인 온라인 세션 진행**
    - 주 1회 리뷰이 세션 진행 : 매주 미션 회고를 진행하며 미션에 대한 공통 피드백을 통해 기술의 본질(객체지향, 아키텍처)에 대한 깊이 있는 고민을 유도하고, 이를 본인의 성장 및 포트폴리오와 연결할 수 있도록 도왔습니다.
    - 월 2회 리뷰어 세션 진행 : 일관성 있는 코드 리뷰 기준을 확립하고, 매주 피드백과 진행 상황을 점검하여 다음 미션의 일정 및 스터디 운영 방식을 지속적으로 개선하는 논의를 진행했습니다.
    - 월 2회 Q&A 세션 : 리뷰어와 리뷰이가 소통할 수 있는 자리를 만들어, 서로의 고민 포인트를 공유하고 답변하는 자리를 가졌습니다.

## Activity (리뷰어)

[리뷰 포인트]

- 단순히 동작하는지를 넘어서 유지보수하기 좋은 구조와 명확한 비즈니스 정책에 초점을 맞춤니다.
- 정답을 제시하기보다 스스로 고민하고 더 나은 구조를 찾아갈 수 있도록 질문을 던지는 방식을 이용합니다.
- 코드 개선을 제안할 때 개인적인 취향이 아니라 가독성, 유지보수성, 객체의 책임 분배 등 명확한 ‘이유와 기준’을 제시하려 노력합니다.

[코드 리뷰 리스트]

| Project                                         | Reviewee | Pull Request |
|-------------------------------------------------| --- | --- |
| **Spring MVC </br> (25.02.02 ~ 25.02.08)**            | 도요 | [중간 제출 PR](https://github.com/next-step/spring-roomescape-playground/pull/400), [최종 제출 PR](https://github.com/next-step/spring-roomescape-playground/pull/403) |
| **Spring JDBC </br> (25.02.09 ~ 25.02.22)**           | 망고 | [중간 제출 PR](https://github.com/next-step/spring-roomescape-playground/pull/410), [최종 제출 PR](https://github.com/next-step/spring-roomescape-playground/pull/420) |
| **Spring Core </br> (25.02.23 ~ 25.03.05)**           | 러키 | [최종 제출 PR](https://github.com/next-step/spring-roomescape-playground/pull/429) |
| **Spring MVC (인증) </br> (25.03.06 ~ 25.03.19)**       | 곰곰 | [중간 제출 PR](https://github.com/next-step/spring-basic-roomescape-playground/pull/128), [최종 제출 PR](https://github.com/next-step/spring-basic-roomescape-playground/pull/134) |
| **Spring Data JPA </br> (25.3.25  ~ 25.04.12)** | 파도 | [중간 제출 PR](https://github.com/next-step/spring-basic-roomescape-playground/pull/141), [최종 제출 PR](https://github.com/next-step/spring-basic-roomescape-playground/pull/144) |
