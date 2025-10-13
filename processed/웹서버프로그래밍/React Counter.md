## React Counter

### 개발 환경 및 설치 확인

* Node.js 버전 확인 -> **`node -v`**
* npm 버전 확인 -> **`npm -v`**
* Node.js 설치 경로 환경변수 추가 -> **`C:\Program Files\nodejs`**
* PowerShell 실행 정책 변경 -> **`set-executionpolicy remotesigned`**

### 프로젝트 생성 및 실행 명령어

* React 프로젝트 생성 (Vite) -> **`npm create vite@latest [프로젝트명]`**
* 프로젝트 폴더 이동 -> **`cd [프로젝트명]`**
* 패키지 설치 -> **`npm install`**
* 개발 서버 실행 -> **`npm run dev`**
* 설치 및 실행 한번에 -> **`npm install && npm run dev`**
* 로컬 실행 주소 -> **`http://localhost:5173/`**

### React 핵심 개념 & 코드

* 상태 관리 Hook -> **`useState`**
* 상태 갱신 함수 -> **`setCount`**
* 비동기 상태 처리 방식 -> **`Asynchronous`**
* 최신 상태 반영 위한 업데이트 -> **`Functional Update`**
* 이전 상태 값 참조 변수 -> **`prev`**
* JSX에서 다중 요소 감싸기 -> **`<> </>`**
* JSX에서 클래스 지정 속성 -> **`className`**

### 배포 관련

* Vite 설정 파일 -> **`vite.config.ts`**
* 자동 배포 라이브러리 설치 -> **`npm install gh-pages --save-dev`**
* package.json 스크립트 (사전 빌드) -> **`predeploy: npm run build`**
* package.json 스크립트 (배포 실행) -> **`deploy: gh-pages -d dist`**
* GitHub Pages 배포 실행 -> **`npm run deploy`**
* GitHub Pages 배포 브랜치 -> **`gh-pages`**

### HTML & 리소스 관련

* HTML 타이틀 변경 -> **`<title>React 카운터</title>`**
* Favicon 파일 이름 -> **`favicon.png`**
* HTML에서 파비콘 지정 -> **`<link rel="icon" type="image/png" href="/favicon.png" />`**

### 배포 플랫폼 (대안)

* 무료 클라우드 플랫폼 -> **`AWS Free Tier`**, **`Oracle Cloud Free Tier`**
* 웹 배포 서비스 -> **`Netlify`**, **`Vercel`**, **`Render`**, **`Cloudflare Pages`**, **`Replit`**, **`Firebase`**, **`InfinityFree`**
