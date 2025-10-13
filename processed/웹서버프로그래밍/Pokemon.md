## Pokemon (React Project)

### 프로젝트 생성 및 실행 명령어

* React 프로젝트 생성 (Vite) -> **`npm create vite@latest [프로젝트명]`**
* 프로젝트 폴더 이동 -> **`cd [프로젝트명]`**
* 패키지 설치 -> **`npm install`**
* 개발 서버 실행 -> **`npm run dev`**
* 로컬 실행 주소 -> **`http://localhost:5173/`**
* 실행 중지 -> **`Ctrl + C`**
* GitHub Pages 배포 실행 -> **`npm run deploy`**

### React Router

* React Router 설치 -> **`npm install react-router-dom`**
* Link 태그 이동 속성 -> **`to`**
* 다중 경로 정의 컨테이너 -> **`<Routes>`**
* 단일 경로와 컴포넌트 매핑 -> **`<Route>`**
* URL 파라미터 추출 Hook -> **`useParams`**
* GitHub Pages 대응 라우터 -> **`HashRouter`**

### TanStack Query (React Query)

* TanStack Query 설치 -> **`npm install @tanstack/react-query`**
* Query 클라이언트 객체 -> **`QueryClient`**
* 전체 앱 감싸는 Provider -> **`QueryClientProvider`**
* 서버 데이터 요청 Hook -> **`useQuery`**
* 데이터 변경 처리 Hook -> **`useMutation`**
* 캐싱 식별자 -> **`queryKey`**
* 데이터 요청 함수 -> **`queryFn`**
* 데이터 동기화 전략 -> **`SWR (Stale-While-Revalidate)`**

### Axios & API 요청

* Axios 설치 -> **`npm install axios`**
* 포켓몬 목록 API -> **`https://pokeapi.co/api/v2/pokemon?limit=30`**
* 포켓몬 상세 API -> **`https://pokeapi.co/api/v2/pokemon/25`**
* 포켓몬 종 API -> **`https://pokeapi.co/api/v2/pokemon-species/25`**
* Axios 인스턴스 생성 메서드 -> **`axios.create()`**
* 비동기 함수 키워드 -> **`async/await`**
* 병렬 비동기 처리 -> **`Promise.all`**

### Tailwind CSS

* Tailwind 설치 -> **`npm install tailwindcss@latest @tailwindcss/vite@latest -D`**
* Tailwind 설정 파일 -> **`vite.config.js`**
* 전역 CSS 초기화 -> **`src/index.css`**
* JSX에서 클래스 속성 -> **`className`**
* Tailwind 색상/스타일 예시 -> **`bg-white`**, **`text-lg font-bold`**, **`hover:scale-105`**

### 비동기 처리 (Asynchronous)

* 콜백 중첩 문제 -> **`Callback Hell`**
* 약속 기반 비동기 객체 -> **`Promise`**
* 동기 코드처럼 작성하는 비동기 방식 -> **`async/await`**
* 에러 발생 시 조기 종료 패턴 -> **`Guard Clause`**

### 상세 정보 및 타입 처리

* 포켓몬 타입별 색상 지정 -> **`typeColors.js`**
* 포켓몬 이름 한국어 변환 -> **`species.names.find(...language.name === "ko")`**
* 배열 문자열 합치기 -> **`join(", ")`**
* 능력치 데이터 -> **`stats`**
* 대표 타입에 따른 색상 클래스 -> **`headerStyle`**

### 배포 관련

* GitHub Pages 자동 배포 라이브러리 설치 -> **`npm install gh-pages --save-dev`**
* package.json 배포 스크립트 -> **`"predeploy": "npm run build"`**, **`"deploy": "gh-pages -d dist"`**
* Vite 설정 파일에서 배포용 경로 설정 -> **`base: '/[repository]/'`**

### HTML & 리소스

* 프로젝트 타이틀 변경 -> **`<title>포켓몬</title>`**
* 파비콘 설정 -> **`<link rel="icon" type="image/png" href="/pikachu.png" />`**
