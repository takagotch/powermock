### powermock
---
https://github.com/powermock/powermock

```java
@RunWith(PowerMockRunner.class)
@PrepareForTest( { YourClassWithEgStaticMethod.class } )
public class YourTestCase {
}

@PowerMockIgnore("org.myproject.")
@PrepareForTest(MyClass.class)
@RunWith(PowerMockRunner.class)
public class MyTest {
}

powermock.global-ignore="org.myproject."
powermock.global-ignore="org.myporject.*","org.3rdpatproject.SomeClass"
mockito.mock-maker-class=mock-aker-inline

public class ServiceHolder {
  private final Set<> services = new HashSet<>();
  public void addService(Object service){
    service.add(service);
  }
  public void removeService(Object service){
    services.remove(service);
  }
}
/*
https://github.com/powermock/powermock/wiki/Bypass-Encapsulation
/*
```

```
```

```
```


