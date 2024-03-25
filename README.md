# 간단한 온라인 포럼 (Simple Online Forum)

간단한 온라인 포럼 프로젝트는 사용자가 질문을 올리고 답변할 수 있는 기본적인 포럼을 제공합니다. 

## 기능

- 사용자 등록과 로그인 기능
- 질문을 올리고 답변할 수 있는 포럼
- 태그 기능을 통한 포스트 분류
- 검색 기능
- 사용자 프로필 페이지

## 사용 기술

- Spring Boot
- Spring Data JPA
- H2 Database (임베디드)
- RESTful API

## 설치 및 실행

1. 프로젝트를 클론합니다.

    ```bash
    git clone https://github.com/yourusername/simple-online-forum.git
    cd simple-online-forum
    ```

2. 프로젝트를 빌드하고 실행합니다.

    ```bash
    ./gradlew bootRun
    ```

3. 웹 브라우저에서 `http://localhost:8080`에 접속하여 포럼을 확인합니다.

