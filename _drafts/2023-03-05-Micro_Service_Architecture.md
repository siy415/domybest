---
title: 마이크로 서비스
date: 2023-03-05 09:52 +0900
categories: [study, platform]
tags: [perellelcomputing, distributedcomputing, book, reading, habit, selfdevelopment, review]     # TAG names should always be lowercase
comments: true
img_path: /assets/img/post/2023-03-05/
---

# 마이크로 서비스란?
소프트웨어가 잘 정의된 API를 통해 통신하는 소규모의 독립적인 서비스로 구성되어 있는 경우의 소프트웨어 개발을 위한 아키텍처 및 조직적 접근 방식.

## 기존의 서비스 방식과 비교
### 모놀리식 서비스
- 모놀리틱 아키텍쳐
    - 모든 프로세스가 결합된 단일 구조로 실행되는 서비스
- 장점
    - 단순한 구조로 인한 개발에 편리
    - 통합 시나리오 테스트 간편
    - 모든 코드가 하나의 묶음이기 때문에 배포도 매우 편리

![iamge](01_monolithic_micro_diff.png){.center}
_모놀리틱 아키텍쳐와 마이크로 서비스의 차이_


마이크로 서비스 : http://guruble.com/%EB%A7%88%EC%9D%B4%ED%81%AC%EB%A1%9C%EC%84%9C%EB%B9%84%EC%8A%A4microservice-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-%EA%B7%B8%EA%B2%83%EC%9D%B4-%EB%AD%A3%EC%9D%B4-%EC%A4%91%ED%97%8C%EB%94%94/
<br>
이벤트 소싱 : https://martinfowler.com/eaaDev/EventSourcing.html