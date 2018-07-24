Ant / Maven / Gradle
============

# Ant

Apach Ant, 2000년에 공개, 자바 프로젝트용 빌드 도구<br/>

- 각 프로젝트에 대한 XML 기반 빌드 스크립트 작성
- 주요 장점은 절차적인 프로그램 개념을 기반으로 빌드 절차 제어
- remote repository를 가져올 수 없었음 (Apach IVY 도입)
- 스크립트의 재사용이 어려움

# Maven

Apach Maven, 2004년에 공개, 자바 프로젝트 관리/빌드 도구<br/>

- Apach Ant 의 대안
- XML 기반 빌드 스크립트 작성
- 프로젝트의 전체적인 라이프사이클을 관리하는 도구
- remote repository를 가져올 수 있음
- pom.xml

# Gradle

Gradle, 2012년에 공개, 프로젝트 구성 및 빌드 도구<br/>

- Grooby 기반의 DSL(Domain Specific Language)<br/>
Maven 의 정적인 형태의 XML 기반인 점을 대안으로 Grooby 빌드 스크립트 사용
- 멀티플랫폼 프로젝트에도 적합(상위 스크립트, 하위 스크립트 독립적으로 작성)
- 상속이 아닌 주입
- remote repository를 가져올 수 있음
