> 인프런 '처음 만난 리액트(React)'를 수강하며 정리한 내용입니다.

https://www.inflearn.com/course/%EC%B2%98%EC%9D%8C-%EB%A7%8C%EB%82%9C-%EB%A6%AC%EC%95%A1%ED%8A%B8/dashboard

<br/>

# Node.js 설치
## Node.js
- 네트워크 애플리케이션 개발에 사용되는 소프트웨어 플랫폼
## NPM
- Node Package Manager
- 자바스크립트 런타임 환경인 Node.js의 패키지 관리자
- Node.js를 설치하면 같이 설치됨
## 설치
- 공식 사이트(https://nodejs.org/ko)에서 설치 진행



<br/><br/>

# 리액트 소개
## 리액트
- UI(사용자 인터페이스)를 위한 자바스크립트 기반 라이브러리
## UI 라이브러리
### NGULAR.js
- 구글에서 만든 오픈소스 프레임워크
- 서비스 종료
### React.js
- Meta에서 만든 라이브러리
### Vue.js
- 중국 1인 개발자가 만든 오픈소스 프레임워크

<br/><br/>

# 리액트 장점
## 1. Virtual DOM
- DOM : Document Object Model, 하나의 웹사이트에 대한 정보를 모두 담고 있는 것
- 웹페이지와 실제 DOM 사이에서 중간 매개체 역할을 하는 가상 DOM
- 화면의 정보가 업데이트됨 = DOM이 수정됨
- React는 DOM을 직접 수정하는 것이 아니라 Virtual DOM에서 업데이트해야할 최소한의 부분만 찾아서 업데이트함
## 2. Component-Based
- 레고 블록 조립하듯 컴포넌트들을 모아서 개발
- 리액트로 이뤄진 웹페이지는 여러 개의 컴포넌트로 이루어져 있음
## 3. 재사용성(Reusability)
- 다시 사용이 가능한 성질
- 재사용성이 높으면?
    - 개발 기간이 단축됨
    - 유지 보수가 용이
- 리액트와 재사용성
    - 각 컴포넌트들은 여러 곳에서 재사용될 수 있어 재사용성이 높음
## 4. 활발한 지식공유 및 커뮤니티
## 5. React Native를 통해 모바일 앱 개발을 할 수 있음
- 안드로이드, 아이폰 앱을 한번에 개발할 수 있음

<br><br/>

# 리액트 단점
## 1. 방대한 학습
- Virtual DOM, JSX, Component, State, Props 등
- 버전이 업데이트되면서 계속 바뀜

## 2. 높은 상태관리 복잡도
- State를 잘 관리하는 것이 중요함
- 규모가 커질 수록 복잡도가 증가함