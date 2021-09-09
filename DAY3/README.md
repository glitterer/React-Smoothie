## DAY3 Study
### 우리가 styled-components로 만드는 컴포넌트를 기존의 CSS방식의 스타일링을 대체하도록 만드는 실습<br/>(DAY2에 이어서...)

* **ch5-my-app-style_AppLogo 컴포넌트 사용_AppLogo회전X:** 애니메이션이 포함된 .App-logo 클래스를 styled-components로 변경
* **ch5-my-app-style_AppLogo 컴포넌트 사용_AppLogo회전O:** styled-components로 변경 후, 회전하지 않는 logo가 회전 하도록 수정
* **ch5-my-app-style_AppLogo_keyframes:** 여러 곳에서 같은 애니메이션을 사용할 때, 애니메이션을 분리해서 사용 가능<br/>
  ==> ```{ keyframes }``` 사용<br/>
  ==>```@keyframes App-logo-spin``` 부분 삭제<br/>  
* **ch5-my-app-style_AppLink 수정:** .App-link 클래스를 styled-components로 변경

***
**공부/파일 순서<br/>**
: AppLogo 컴포넌트 사용_AppLogo회전X --> AppLogo 컴포넌트 사용_AppLogo회전O --> keyframes --> AppLink 수정
