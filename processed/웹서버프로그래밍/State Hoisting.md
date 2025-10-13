## React & State Hoisting

### 프로젝트 생성 및 실행 명령어

* React 프로젝트 생성: Vite 사용 -> **`npm create vite@latest [프로젝트명]`**
* 프로젝트 폴더 이동 -> **`cd [프로젝트명]`**
* 패키지 설치 -> **`npm install`**
* 개발 서버 실행 -> **`npm run dev`**
* 로컬 실행 주소 -> **`http://localhost:5173/`**

### GitHub Pages 배포 관련

* Vite 설정 파일 -> **`vite.config.ts`**
* GitHub Pages 배포용 라이브러리 설치 -> **`npm install gh-pages --save-dev`**
* package.json 스크립트 추가:

  * predeploy -> **`npm run build`**
  * deploy -> **`gh-pages -d dist`**
* 배포 실행 -> **`npm run deploy`**
* GitHub Pages 브랜치 설정 -> **`gh-pages`**

### 핵심 개념 (State Hoisting & React 철학)

* 상태를 컴포넌트 내부에서 관리하는 것 -> **`Stateful Component`**
* 상태를 가지지 않고 props로만 동작하는 것 -> **`Stateless Component`**
* 상태 끌어올리기 -> **`State Hoisting`**
* 부모에서 상태 관리 후 자식으로 전달 -> **`props`**
* 구조 분해 할당 -> **`Destructuring`**
* 단방향 데이터 흐름 -> **`Unidirectional Data Flow (UDF)`**
* React에서 항목 식별을 위해 필요한 속성 -> **`key`**

### 코드 관련 주요 요소

* 상태 생성 Hook -> **`useState()`**
* 이벤트 핸들러 전달 -> **`onClick`**
* 합계 계산 메서드 -> **`reduce()`**
* 배열 복사/불변성 유지 -> **`Spread syntax (...)`**
* 배열 순회/컴포넌트 생성 -> **`map()`**

---

필기/시험 대비 시에는 위 항목의 **명령어, 핵심 개념, 코드 키워드**가 그대로 빈칸 문제로 출제될 가능성이 높습니다.
