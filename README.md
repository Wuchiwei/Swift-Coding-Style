# Swift-Coding-Style

Reference https://github.com/raywenderlich/swift-style-guide

## Spacing
1. You should left a space between an English character and Chinese character.

**Preferred:**

```
歡迎加入 AppWorks School 大家庭
```

**Not Preferred:**

```
歡迎加入AppWorks School大家庭
```

2. Method braces and other braces (if/else/switch/while etc.) always open on the same line as the statement but close on a new line.

**Preferred:**

```swift
if isRainning {
  // Do something
} else {
  // Do something else
}
```

**Not Preferred:**

```swift
if isRainning
{
  // Do something
}
else {
  // Do something else
}

or 

if isRainning{
  // Do something
}else{
  // Do something else
}
```

3. Type Notation: You should left a space after a `:` mark for type notation, and leave no space before the `:` mark.

**Preferred:**

```swift

var friends: [String] = []

var scores: [String: Int] = [:]

func greeting(name: String) {

}
```

**Not Preferred:**

```swift

var friends:[String] = []

var scores:[String:Int] = [:]

func greeting(name :String) {
    
}
```

4. Left space before and after any operator.

**Preferred:**

```swift

1 + 2 = 3

var count: Int = 10
```

**Not Preferred:**

```swift
1+2=3

var count: Int=10
```

5. Left space after curly brace in method declaration and return type. If return type is `Void`, we just omit it.

**Preferred:**

```swift
func greeting() {

}

func add(a: Int, b: Int) -> Int {

}
```

**Not Preferred:**

```swift
func greeting() -> Void {
    
}

func greeting(){

}

func add(a: Int, b: Int)->Int{
    
}
```