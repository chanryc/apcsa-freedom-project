# Entry 4
## Start of MVP 3/18/24

Between the previous entry and this blog entry, I have begun progressing towards making the MVP of the cookbook recipe app. The MVP is essentially the minimum viable product of an app with its basic functionality. Instead of nitpicking the smallest details, an MVP ensures the necessary parts are completed first. My partners and I have compiled a set list of tasks to be completed and done on the app before certain deadlines.

I've made progress towards creating the github repository for the recipe app. Since I never connected my Xcode to my github ever, I had to figure out how to link my github account to Xcode (this way I would be able to clone, commit, push, and pull from a github repository). I watched [this video](https://youtu.be/T3QPQc0LW5w?si=DdZQ21YvQYMrqu22) and I was successfully able to connect and push one of my experiment projects to my github account. 


As for learning my tool, I've watched part 11 and 12 of the Swift playlist. This time, I took into deeper consideration of what components I would be using for the project. I noted down important key basics:

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

In addition to watching the videos, I finally took the chance to learn from the [documentation](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/closures/) about closures. Closures are self-contained blocks of code that can be passed around and used in other parts of code. It's similar to how a function behaves, except closures are more simplified. After reading a bit about closures I felt that it would definitely be something that I would like to use in the recipe app, and so I noted down that I would read more further into closures. Although the documentation is useful at times, I find myself going back to YouTube to search video explanations, as I end up getting confused in the words. 

I am currently in stage three and four of the EDP, which is brainstorming possible solutions and planning the most promising solution. Brainstorming and planning go hand in hand, and so my partners and I planned out out MVP plan of all the lists of tasks we were to complete before set deadlines. We decided on the most essential features and components of our app.

Skills that I have achieved in this blog entry are *how to google* and *how to learn*. Xcode was a new environment for my partners and I, and so we all had to google search for specific key phrases like "connect xcode to github" or "link github account to xcode" in order for us to be able to collaborate on a repository together. I especially needed to know how to learn as I had to a few video tutorials before I fully understood how to add my github to Xcode.

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
