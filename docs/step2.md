# Step 2: Our first Angular component


## app 하위 폴더 만들기
```
$ mkdir app
```

## 컴포넌트 파일 만들기

```js
import { Component } from '@angular/core';
@Component({
  selector: 'my-app',
  template: '<h1>My First Angular 2 App</h1>'
})
export class AppComponent { }
```

- 한개 혹의 이상의 import는 우리가 필요한 레퍼런스들을 알린다.
- @Component 데토레이터는 어떤 템플릿을 사용하고 컴포넌트를 어떻게 만들지 Angular에게 알려준다.
- 컴포넌트 class는 템플릿을 통해서 뷰의 행동와 외형을 조절한다.
