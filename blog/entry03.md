# Entry 3
## Learning Swift Pt. 2 2/12/24

Continuing with the [Swift Tutorial playlist](https://www.youtube.com/playlist?list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW), I followed along and watched parts 6-10. I took down important notes and code snippets:

__Part 6 - Loops__
* about loops like `for in` and `while`
  * The `for in` is similar to a `for each`

![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/04d93a26-e35c-419c-96e9-68adc1bb1cbd)

__Part 7 - Optionals & Unwrapping__
* optional is a type that represents either a wrapped value or a nil value
  * `dataType?` or it will be written like `Optional<dataType>` 
* optionality is a good way to represent errors
  * gives flexibility with assigning values of a particular variable

__Part 8 - If Else Conditionals__
```java
// conditionals
if condition {
  // stuff
} else if condition {
  // stuff
} else {
  // stuff
}
```

__Part 9 - Guard Statements__
```java
// guard statements
// - they are much more "cleaner" (simpler) than if/else statements
guard conditional1, conditional2 else { wtvHappensIfConditionalsAreFalse }
  // code that will run if conditions are met
```
* using guards to unwrap optionals and also a simpler way than if/else statements are the most common
  * example of guard statement:
    * ![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/e2b90bcf-4b96-4be4-8466-57293c559ed8)

__Part 10 - Enums & Switch Statements__
* enum is a special data type that allows variables to be predefined 
```java
// enums and switch statements
//An enum is another way to represent cases (used to represent multiple states)

enum States {
  case InProgress, Aborted, Complete, WillStart
}

let current = States.InProgress

enum States: String{}
^ enum States inherits strings
```

* switch allows you to inspect a value and match it with a case
```java
func checkStats() {
  switch current {
    case .InProgress:
      // CODE
      break
    case .Aborted:
      // CODE
      break
    case .Complete:
      // CODE
      break
    case .WillStart:
      // CODE
      break
  }
}
```
* since `current` is set to `states.InProgress` (from code snippet in enum section), whatever code that is for `.InProgress will run

Though I initially planned to do a mini project to test my skills on Swift, I felt unprepared to start one, so I decided only to continue learning Swift from the YouTube playlist. Along with the YouTube video, I started looking at [Swift's Documentation](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/thebasics) to learn more about Swift. I skimmed through the very beginning of "The Basics" section as I saw overlap with what I learned from the videos, so I didn't take any notes of that part. 

Currently, I am still in stage two of the EDP, with all the research and learning I am still doing with Swift. I am starting to build a more solid foundation of what Swift is capable of doing, and how I can use Swift to code my freedom project.

Skills that I have developed during this blog entry are *time management* and *organization*. I found myself not having much time during the week to tinker deeply with Swift, especially with the workload from other classes. With that I still held myself responsible for tinkering as much as I possibly could with Swift, thus managing my time wisely. While learning from the YouTube videos, I had to organize my notes neatly so that if I ever needed to refer back to them, I would be able to understand them.

Next up I plan to dive more deeply into the documentation and learn from there instead of watching the videos. I feel like the videos are too broad, and they don't go too in-depth with the topic like how documentations do. After looking through the documentation, I think will finally be ready to make a mini project, or start figuring out what specific concepts I will need to implement on my cookbook recipe app.  

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
