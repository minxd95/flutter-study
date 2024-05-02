### 핵심요약

- `StatelessWidget`은 상태 관리가 필요 없을 때 사용한다. 하나의 클래스로 이루어졌고 `build()` 함수는 생명주기 동안 단 한번만 실행된다.
- `StatefulWidget`은 상태 관리가 필요할 때 사용한다. `StatefulWidget` 클래스와 `State` 클래스로 이루어졌고 생명주기 동안 `build()` 함수가 여러 번 실행될 수 있다.
- `PageView` 위젯을 이용하면 스와이프로 페이지를 변경하는 UI를 쉽게 구현할 수 있다.
- `Timer.periodic()`을 이용해서 특정 함수를 주기적으로 실행할 수 있다.
- `PageController`를 사용해서 `PageView를` 조작할 수 있다.
- `StatefulWidget`의 `initState()`에 코드를 작성하면 `State`가 생성될 때 딱 한 번만 실행한다.
- `SystemChrome.setSystemUIOverlayStyle`을 사용해서 상태바의 색상을 흰색이나 검정색으로 변경할 수 있다.