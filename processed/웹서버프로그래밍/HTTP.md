## HTTP

### 명령어 및 프로토콜 기본

* 하이퍼미디어 문서 전송을 위한 애플리케이션 계층 프로토콜 -> **`HTTP (HyperText Transfer Protocol)`**
* 대표적 하이퍼미디어 문서 형식 -> **`HTML`**
* 웹 브라우저와 웹 서버 간 통신에 사용되는 프로토콜 -> **`HTTP`**

### 핵심 개념 (Conceptual Pillars)

* 요청(Request)과 응답(Response) 모델 기반 동작 -> **`Client-Server Architecture`**
* 웹 통신의 상태를 유지하지 않는 성질 -> **`Stateless`**
* 웹 통신에서 상태를 유지하기 위한 보조 수단 -> **`쿠키(Cookie)`**
* 세션 기반 인증 및 상태 유지 방법 -> **`세션(Session)`**
* 암호화된 안전한 HTTP -> **`HTTPS (HTTP Secure)`**
* URL을 통해 자원을 식별 -> **`Uniform Resource Locator (URL)`**

### 주요 HTTP 메서드

* 데이터 조회 -> **`GET`**
* 데이터 생성 -> **`POST`**
* 데이터 전체 수정 -> **`PUT`**
* 데이터 일부 수정 -> **`PATCH`**
* 데이터 삭제 -> **`DELETE`**
* 서버 연결 확인 (상태 점검) -> **`HEAD`**
* 서버 기능 확인 -> **`OPTIONS`**

### 상태 코드 (Status Codes)

* 요청 성공 -> **`200 OK`**
* 리소스 생성 성공 -> **`201 Created`**
* 잘못된 요청 -> **`400 Bad Request`**
* 인증 실패 -> **`401 Unauthorized`**
* 접근 권한 없음 -> **`403 Forbidden`**
* 요청한 자원이 없음 -> **`404 Not Found`**
* 서버 내부 오류 -> **`500 Internal Server Error`**
