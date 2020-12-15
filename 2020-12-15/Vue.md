# Vuex

~Vue 정점을 찍었다고 생각했는데, 역시 Vuex 쪽은 부족했나보다.~

### Vuex 에서 new WebSocket() 을 넣으려고 했는데 단순히 state 에 넣으니깐 안됐었다.


*이런식으로 객세 스타일로 커밋하니깐 .SOCKET 으로 레퍼런싱 가능*

```js
this.$store.commit({
  type: 'setSocket',
  SOCKET: new WebSocket(SOCKET_URL)
})
```
