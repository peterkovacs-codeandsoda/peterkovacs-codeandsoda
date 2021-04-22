<style>
  .page-header {
    background-image: none;
  }
</style>

# Unity - The Practical Way
## 1. Delegates

### 1.1. Event System
- Participants:
  - Event creators
  - Event listeners
- Application:
  - State-Machine (typeless/typed)
  - Avoid tightly coupled calls and parameter/context propagation
- Constraints:
  - Every Event System defines a 'kind of' behavior
- Event-Driven: anything can and should be an event

### 1.2. Delegates
- C#: type safe function pointer (coupled with context/object)
```
...
public delegate MyDelegateType MyMethod();

public class MyObject {  

  public event MyMethod DelegateMethodName;

  public void DoSomeMagic() {
    if (DelegateMethodName != null) {
      DelegateMethodName();
    }
  }
}
```
- Javascript: no explicit delegate, but Function.bind
```
function createDelegate(func, target) {
    return function() {
        return func.apply(target, arguments);
    };
}

var myObject = { name: "Target!"};
function myMethod() {
    return this.name;
}

var delegate = createDelegate(myMethod, myObject);
alert(delegate());
```

```
var myObject = { name: "Target!"};
function myMethod() {
    return this.name;
}

var delegate = myMethod.bind(myObject);
alert(delegate());
```

### 2. Milestone 3
- Stage spawning mechanism
- Hero basic mechanism
- Prestige system basic mechanism

### 2.1. Demo
- Have fun
