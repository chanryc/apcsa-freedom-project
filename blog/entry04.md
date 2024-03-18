# Entry 4
## Start of MVP 3/18/24

Between the previous entry and this blog entry, I have begun progressing towards making the MVP of the cookbook recipe app. The MVP is essentially the minimum viable product of an app with its basic functionality. Instead of nitpicking the smallest details, an MVP ensures the necessary parts are completed first. I've made progress towards...

As for learning my tool, I've watched part 11 and 12 of the Swift playlist. I noted down important key basics:

__Part 11 - Protocols__
* protocols are a place to declare variables and functions before initializing it
  * especially useful for when those mentioned variables and functions can be used in other classes besides just one 
```java
// protocols
protocol AnyFun {
  var anything: String { get set } // the get set is so the classes can get and set the value of the var

  func anyWords()
  func haveApple() -> Bool
}

// class
class haveApple() ->  {
  var anything: String
  init(var anything: String) {
    self.color = color
  }
}
```

__Part 12 - Strong Versus Weak Memory__
* if something is strong in memory, that means that it won't deleted away by whatever it is tied to (even if we don't use/need it)
  * variables are by default set to strong
* if something is weak in memory, that means that it will be deleted away if the "parent" or whatever it is tied to is deleted
  * ex: weak var balloon = "str"

In addition to watching the videos, I finally took the chance to learn from the [documentation](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/closures/) about closures. Closures are basically self-contained blocks of code that can be passed around and used in other parts of code. It's similar to how a function behaves, except closures are more simplified.

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
