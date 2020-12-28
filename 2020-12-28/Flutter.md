# Flutter 시작!

### StatelessWidget
변경될 일이 없는 위젯 (상태가 없는)

변경하고 싶으면? -> **StatefulWidget**

### StatefulWidget

변수를 final 로 선언하고

생성자 만들어줘야됨 (아직 왠지 모르겠음.)

### setState

StatefulWidget 제네릭으로 갖고 있는 클래스에서

_변수(자동으로 private 이 된다고 함 Dart 문법인듯?) 선언해서 걔를 setState 하면 됨!

```dart
void _changeMessage() {
  setState(() {
    _message = 'Hi Louis!';
  });
}
```

흡사 React 와 비슷..
