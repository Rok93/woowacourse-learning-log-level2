# 우아한테크코스 레벨 2 학습로그를 정리한 저장소 By 로키 


# 체스 웹 미션 (스프링 적용하기) 학습로그 

## [Spring Framework] Spring Core, Spring MVC, Spring JDBC - 4
### 내용
- 브라운의 테스트로 배우는 Spring 학습 테스트 수행 
- 기초적인 사용법 및 기능들 학습 
### 링크
- [브라운의 Spring 학습 테스트](https://github.com/next-step/spring-learning-test)

## [TEST] RestAssured Test Framework 학습 및 활용 - 2 
### 내용
- 브라운의 테스트로 배우는 Spring 학습 
-  RestAssured 공식문서 참조 
### 링크
- [RestAssured Usage Guide](https://github.com/rest-assured/rest-assured/wiki/Usage)

## [REST API]  REST API 디자인 가이드 학습 및 적용 -  3
### 내용 
- REST API 란 무엇인가? 
- REST API 디자인 가이드 학습 및 적용 
### 링크
- [REST API 제대로 알고 사용하기](https://meetup.toast.com/posts/92)
- [스프링부트 : REST 어플리케이션에서 예외처리하기](https://springboot.tistory.com/33) 
- [Spring Guide - 에외 처리 전략](https://www.popit.kr/spring-guide-%EC%97%90%EC%99%B8-%EC%B2%98%EB%A6%AC-%EC%A0%84%EB%9E%B5/) 
- [REST API 정리](https://www.notion.so/rok93/REST-API-9e1cbfb35bd14f86a2c63210945c0039) 

## [패키지 구조] 프로젝트 폴더 구조 - 1
### 내용
- 프로젝트의 패키지 구조는 어떻게 가져가는게 좋을까? 
### 링크
- [김영한님 강의 QnA 중 관련 내용](https://www.inflearn.com/questions/16046) 
- [spring-guide-directory](https://cheese10yun.github.io/spring-guide-directory/)

# 지하철 노선도 관리 미션 학습 로그 

## DAO VS Repository
- [DAO와 REPOSITORY 논쟁](http://egloos.zum.com/aeternum/v/1160846)
- [피드백 내용](https://github.com/woowacourse/atdd-subway-map/pull/135#discussion_r631192384) 

### 태그 
- 아키텍처

## 인수 테스트 VS End To End 테스트
- [피드백 내용](https://github.com/woowacourse/atdd-subway-map/pull/98#discussion_r628005891)
- [[tdd] 인수테스트, 단위테스트, 통합테스트, 전 구간 테스트
 ](https://joont92.github.io/tdd/%EC%9D%B8%EC%88%98%ED%85%8C%EC%8A%A4%ED%8A%B8-%EB%8B%A8%EC%9C%84%ED%85%8C%EC%8A%A4%ED%8A%B8-%ED%86%B5%ED%95%A9%ED%85%8C%EC%8A%A4%ED%8A%B8-%EC%A0%84-%EA%B5%AC%EA%B0%84-%ED%85%8C%EC%8A%A4%ED%8A%B8/)

### 태그
- Test 

## Mock 객체 
- 깊이 공부한 것은 아니지만, 리뷰어가 아래의 참고자료를 공유해주었는데 지금까지는 단순히 Mock 객체가 빠른 피드백을 줄 수 있다는 점에서 장점이 크다고 생각했고, 각 Layer 단위 테스트가 잘 작성되있다면 Mock 객체를 사용하는데 전혀 문제가 없다고 생각했다. 내가 생각하는 것 이상의 많은 논쟁점이 있다는 것을 알게되었다. 
- [Mock 관련 참고자료](https://github.com/woowacourse/jwp-refactoring/pull/2#discussion_r491075672)

### 태그
- Test 

# 지하철 경로조회 / 로그인 미션 학습로그

## JWT
- JWT란 무엇인가? 
- JWT의 구조 
- JWT 사용법 

## 태그 
- 인증
- 인가

## ArgumentResolvers
- Custom Argument Resolver를 등록할 수 있다.
- `@ AuthenticationPrincipalArgumentResolver` 등록 및 사용 
- [공식 문서](https://www.baeldung.com/spring-mvc-custom-data-binder#1-custom-argument-resolver)

## 태그 
- Spring 

# 스프링 협업 미션 학습로그 

## Swagger 
### 내용
- API 문서 작성을 위해 API 문서 자동화 툴인 Swagger 사용 
- RestDocs와 비교하여 비교적 간단하게 API 문서를 작성할 수 있었음 
- Config 설정 코드, 애너테이션 등을 추가해야해서 프로덕션 코드를 더럽힌다는 단점이 있음 
- RestDocs와 비교했을 때, 상대적으로 신뢰도가 떨어짐 
### 태그 
- 문서 자동화

## Interceptor
### 내용 
- 로그인 / 비로그인에 따라 권한을 차등 부여 
- HTTP Method에 따라 1차적으로 필터링 
- OPTIONS(= Preflight 요청), GET 방식의 요청은 모두 허용 
- POST 요청의 경우 Token(=JWT)을 검증하여 올바른 토큰인 경우에만 요청 허용 
### 태그
- Spring

