### 오늘도 갓갓 ES6

setState 할 떄 switch 문으로 고생 안하고 event name 받아서 처리하면 될듯..

```js
this.setState({ [name]: value })
```
이렇게..

좀 더 고급진 표현으로는

```js
switch (name) {
  case 예외처리:
    처리
    break;
  default:
    this.setState({ [name]: value })
    break;
}
```
