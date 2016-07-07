# Step 2: 첫번째 Angular 컴포넌트


## app 하위 폴더 만들기: 프로젝트 루트 폴더에
```
$ mkdir app
```

## 컴포넌트 파일 만들기: 방금 만든 폴더에 `app/app.component.ts`
`app/app.component.ts`
```js
import { Component } from '@angular/core';
@Component({
  selector: 'my-app',
  template: '<h1>My First Angular 2 App</h1>'
})
export class AppComponent { }
```

AppComponent는 애플리케이션의 루트이다.

모든 Angular 앱은 최소 하나의 루트 컴포넌트를 가진다. 관례적으로 `AppComponent`라는 이름으로. 클라이언트 UX를 다루는.
컴포넌트들은 Angular 애플리케이션의 기본 블록이다. 하나의 컴포넌트는 조합된 템플릿을 통해 화면(뷰)의 영역을 컨트롤한다.

QuickStart는 오직 한개의 아주 단순한 컴포넌트를 가진다. 


- 한개 혹의 이상의 `import`는 우리가 필요한 레퍼런스들을 알린다.
- `@Component` 데코레이터는 어떤 템플릿을 사용하고 컴포넌트를 어떻게 만들지 Angular에게 알려준다.
- 컴포넌트 `class는` 템플릿을 통해서 뷰의 행동와 외형을 조절한다.
