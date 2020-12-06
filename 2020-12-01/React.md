# === 노마드 코더  ===

### 3.1 All you need to know about State

알다시피 state 를 직접 변경하려고 하면 안됨.
React render 가 refresh 해주질 않음.


일케 써야됨.
```js
this.setState({
  something: 'Hi'
})
```
React Render 가 새로 갱신해줄거임.


### 3.2 Component Life Cycle

#### Mounting
- ##### constructor()

```js
constructor() {
  super(props)
}
```

- ##### render()

- ##### componentDidMount()
  render 이후

#### Updating

- ##### componentDidUpdate()
  업데이트 되면 render 이후

#### Unmounting

- ##### componentWillUnmount()
  페이지가 바뀌거나 하면서 컴포넌트 없어질 때

### 3.3 Planning the Movie Component

클래스 컴포넌트일 때
**this.state** 안쓰는 개꿀팁 갓갓 ES6

```js
const { somethingData } = this.state
```