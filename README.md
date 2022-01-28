# 소스 설명 (source description)
구매자, 코디네이터, 관리자로 가입
코디네이터는 패션 코디를 등록
구매자는 좋아요, 구독, 알람설정, 코디상품 구매
카카오톡, 구글, 일반회원가입 지원

# 소스 개발스택 (source stack)
spring boot(gradle), mysql, jpa

# 소스 로컬 세팅 및 실행법 (source setting rule)

1.mysql 워크벤치 세팅 (db)

-설치 후 실행:
https://reference-m1.tistory.com/268 (참고)

-connection추가:
hostname : 127.0.0.1
port : 3306
username : root
password : altkzk2gh!

-table create:
/src/main/resources/create_table.txt 참고하여 생성


2.백엔드 서버 실행 (STS 설치가 어려울 경우 3.VSCODE 실행 참조)

-sts 설치 후 실행:
https://justdo-heal.tistory.com/17 (참고)

-소스import:
백엔드 소스를 다운받은 후 경로로 이동
Package Explorer > 우클릭 > Git/Existing Gradle Project로 소스 디렉토리 선택

-server run:
import한 프로젝트 우클릭 > Run As > Spring Boot App

3.백엔드 VSCODE에서 실행
https://gethlemn.tistory.com/28(참고)
백엔드 스프링 디렉토리 아래로 이동
.\mvnw spring-boot:run (스프링 서버 run)

gradle 환경 실행
https://youngwonhan-family.tistory.com/70(참고
gradle  tasks 확장 설치
.\gradlew.bat
.\gradlew bootRun  or (gradlew build)

4.swagger rest api 규격 사용
http://localhost:8080/swagger-ui.html#/
