# [WebFlux](https://heeyeah.github.io/spring/2020-02-29-web-flux/)
WebFlux는 client, server에서 [reactive 스타일](https://m.blog.naver.com/jdub7138/220983291803)의 어플리케이션 개발을 도와주는 모듈

```Reactive Programming의 핵심은 모든 것을 비동기적인 데이터의 Stream으로 간주하고, Observer 디자인 패턴을 활용해서 이러한 비동기 이벤트를 처리하는 것에 있습니다.```

## 키워드
- 비동기
- [Observer 패턴](https://includestdio.tistory.com/40)

# HttpClient 모듈
REST 서비스의 호출 방법을 설명한다.
```jdk.incubator.httpclient는 java9이라 있다는 것만 알고있자. 그리고 이것은 java11에선 java.net.http로 옮겨졌다.```

## 동기
- [RestTemplate](https://velog.io/@soosungp33/%EC%8A%A4%ED%94%84%EB%A7%81-RestTemplate-%EC%A0%95%EB%A6%AC%EC%9A%94%EC%B2%AD-%ED%95%A8): Spring 3부터 지원, REST API 호출이후 응답을 받을 때까지 기다림 - blocking

## 비동기
- [AsyncRestTemplate](https://055055.tistory.com/11): Spring 4에 추가된 비동기 RestTemplate

## 동기 & 비동기
-  [WebClient](#) (webflux를 디펜젼시에 추가): spring 5에 추가된 논블럭, 리엑티브 웹 클라이언트

### 참고
[RestTemplate vs WebClient](https://happycloud-lee.tistory.com/220)

# WAS
--

### 참고
[tomcat vs jetty](https://baek-kim-dev.site/119)
