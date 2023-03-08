### 웹 퍼블리셔

- 웹 표준, UI 인터페이스, 웹 접근성
- 화면 인터렉션 구현의 비중이 크다

### 프론트엔드 개발자

- 데이터를 연결하고
- 다양한 js 프레임워크를 사용한다
- API등을 사용해 웹퍼블리셔가 넘겨준 문서를 실제로 동작할 수 있도록 정리,작업해주는 역할을 맡는다

<br/>

## JQuery vs React

- JQuery의 특징

  - HTML/DOM 조작
  - HTML 이벤트 메서드를 쉽게 사용
  - CSS 조작 기능
  - 이펙트나 애니메이션 주기 편하다

- React의 특징

  - UI의 특정 부분을 만들어서 재사용
  - **JSX**를 사용하면 DOM을 직접 조작 할 수 있다
    - **JSX**를 사용하여 불필요한 HTML, CSS작성을 **JSX**로 통합하였다
  - **Virtual DOM**을 제공하여 웹 사이트의 성능을 높인다

- 결론
  - 두개 모두 자바스크립트 라이브러리이다
  - `JQuery`는 `Javascript`의 브라우저 호환성이 좋아진 만큼<br> 사용할 이유가 없어졌다

### Express란

- `Node.js`를 위한 빠르고 개방적인 간결한 웹 프레임워크
  - `Node.js`는 `javascript`로 브라우저가 아니라 서버를 구축하고, 서버에서 `javascript`가 작동되도록 해주는 런타임 환경
- express란 Node.js를 사용하여 쉽게 서버를 구성할 수 있게 만든 클래스와 라이브러리의 집합체

### NPM(Node Package Manger)

- 자바스크립트 라이브러리를 설치하고 관리하는 패키지 매니저이다
- `java`랑 비교하면 `Maven`정도

### 부트스트랩

- 각종 레이아웃, 버튼, 입력창 등의 디자인을 CSS와 Javscript로 만들어 놓은 것이다

## CSS 작성방법

- 일반적인 CSS파일로 작성하기
- CSS-Module로 작성하기
- Sass로 작성하기
- **css-in-js로 작성하기**

  ```jsx
  const Wrapper = styled.div`
    padding: 16px;
    width: calc(100% - 32px);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  `;
  ```
