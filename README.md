# thatknow(그거알아?)
체감온도에 맞는 옷을 사용자에게 추천하는 서비스 개발 프로젝트

현재 지역의 날씨를 기반으로 알고리즘을 통해 체감온도를 계산하고 그에 맞는 옷을 추천한다

 - GPS 좌표 값을 기상청API 지역 데이터에 맞게 정규화
 - 현재 지역에 대한 예보된 날씨 정보 가져옴
 - 체감 온도 계산
 - 날씨와 체감 온도에 맞게 옷 추천


# 프로젝트 구성

## 개발 환경
 - Spring Boot 3.1.1(Dependencies: Jpa, Thymeleaf, Lombok, Spring Web, MariaDB Driver)
 - redhat openjdk 17
 - MariaDB 10.11.4 Ver

