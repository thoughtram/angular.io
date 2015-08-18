```
import {Component, View, bootstrap} from 'angular2/angular2';

@Component({
  selector: 'my-app'
})
@View({
  template: '<h1 id="output">Dependency Injection is cool</h1>'
})
class AppComponent { }

bootstrap(AppComponent);

```