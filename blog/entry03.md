# Entry 3
## Learning Swift Pt. 2 2/12/24

Continuing with the [Swift Tutorial playlist](https://www.youtube.com/playlist?list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW), I followed along and watched parts 6-10. I took down important notes and code snippets:

__Part 6 - Loops__
* about loops like `for in` and `while`
  * the `for in` is similar to a `for each`

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

Though I initially planned to make a mini project to test my skills on Swift, I found myself feeling unprepared to start one, hence I only continued with learning Swift from the YouTube playlist.
  



[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
