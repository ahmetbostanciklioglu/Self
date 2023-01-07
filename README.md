# Self


**Self:**
```
struct SelfUsingInitializer1 {
    var property: String
    
    init(property: String) {
        self.property = property
    }
}

SelfUsingInitializer1(property: "Ahmet")
```

```
struct SelfUsingInitializer2 {
    var property1: Int
    var property2: Int = 7
    init(property1: Int) {
        self.property1 = property1
    }
}
let object1 = SelfUsingInitializer2(property1: 12)
```
