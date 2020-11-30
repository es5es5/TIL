=== 노마드 코드 React #3.0 ===
함수형 컴포넌트는 그냥 함수.
클래스 컴포넌트는 그냥 클래스.

함수는 뭔가를 리턴함. 그걸 screen 에 뿌려짐

클래스는 리액트 컴포넌트를 상속 받아서 리액트 관련된 거를 쓸 수 있음.
예를들어 render(){ return; }

React 는 클래스 컴포넌트의 render 를 자동으로 실행함. 그러므로 화면에 뿌려줄 수 있음.

그럼 둘이 차이는 뭐임
바로 **state**.

```js
state = {}
```

state 는 React 에서 쓰는 data 임.
**data 는 변함.**

클래스 안에 있기 때문에 **this** 키워드로 호출


onClick 은 React 에서 기본적으로 있는 props 임

~~JavaScript 빡고수가 되기 위해 ES6 Class 를 공부해야겠음~~