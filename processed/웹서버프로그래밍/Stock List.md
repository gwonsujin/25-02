## React Stock List Project

### 프로젝트 생성 및 실행 명령어

- Vite 기반 React 프로젝트 생성 -> **`npm create vite@latest [프로젝트명]`**
- 프로젝트 폴더 이동 -> **`cd [프로젝트명]`**
- 패키지 설치 -> **`npm install`**
- 개발 서버 실행 -> **`npm run dev`**
- 로컬 실행 주소 -> **`http://localhost:5173/`**
- PowerShell 버전 확인 -> **`$host.version`**
- PowerShell 7 이상 설치 필요 -> **`PowerShell-7.5.3-win-x64.msi`**

### Tailwind 설정 및 사용

- Tailwind 설치 명령어 -> **`npm install tailwindcss@latest @tailwindcss/vite@latest -D`**
- Vite 설정 파일 -> **`vite.config.js`**
- CSS 파일에 추가 -> **`@import 'tailwindcss'`**
- JSX에서 클래스 지정 속성 -> **`className`**
- Tailwind 주요 속성: **`bg-gray-100`**, **`min-h-screen`**, **`p-8`**, **`flex`**, **`items-center`**, **`grid-cols-2`**, **`max-w-7xl`**

### 주요 React Hooks & 개념

- 상태 관리 Hook -> **`useState`**
- 사이드 이펙트 처리 Hook -> **`useEffect`**
- 데이터 요청 함수 -> **`fetch`**
- 비동기 처리 키워드 -> **`async/await`**
- Promise 메서드 -> **`then / catch`**
- React 개발 모드 경고 감지 -> **`Strict Mode`**

### API 및 데이터 처리

- Yahoo Finance 데이터 요청 URL -> **`https://query1.finance.yahoo.com/v8/finance/chart/[티커]?interval=1d&range=1d`**
- CORS 정책 -> **`Cross-Origin Resource Sharing`**
- CORS 우회 프록시 -> **`https://api.allorigins.win`**
- JSON 데이터 접근 -> **`response.json()`**

### 에러/로딩 처리

- 에러 상태 관리 변수 -> **`error`**
- 로딩 상태 관리 변수 -> **`loading`**
- 로딩 화면 처리 클래스 -> **`animate-pulse`**

### 한국 주식 & 통화 처리

- KOSPI 티커 접미사 -> **`.KS`**
- KOSDAQ 티커 접미사 -> **`.KQ`**
- 한국 주식 통화 -> **`₩`**
- 해외 주식 통화 -> **`$`**
- 숫자 포맷팅 (한국 주식) -> **`toLocaleString()`**
- 숫자 포맷팅 (해외 주식) -> **`toFixed(2)`**

### 주식 시세 링크 연결

- 한국 주식 상세 URL -> **`https://finance.naver.com/item/main.naver?code=[종목코드]`**
- 해외 주식 기본 URL -> **`https://www.google.com/finance/quote/[티커]:[거래소]`**
- NYSEArca 보정 -> **`meta.exchangeName === 'PCX' ? 'NYSEARCA' : ...`**
- 보안 속성 -> **`rel="noopener noreferrer"`**

---

이 목록은 시험 대비용으로 **명령어, Hook, API 주소, Tailwind 속성, 핵심 개념**을 빠르게 암기할 수 있도록 정리되었습니다.
