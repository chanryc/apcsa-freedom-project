# Entry 2
## Learning Swift 12/18/23

As I was set in stone with Swift as my tool, I continued learning Swift step-by-step by following YouTube tutorials. I continued with the [Swift tutorial playlist](https://www.youtube.com/playlist?list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW), and I watched parts 3-5 while coding and taking down important notes:

__Part 3__
* Swift assumes variable type but it can be declared like `var varName: dataType = "anything here"`
* `import UIKit` allows you to import user interface elements
  
__Part 4__
```java
// function format
func funcName(paramName1: value, randomNum: Int) -> expectedReturnVal {
return paramName1 + randomNum
}
```
^ I learned how to make/call a function, parameters, how to make a function return something, and how a return type is set in a function

__Part 5__
* My own version of a class after following along with the video:
```java
import SwiftUI
// CLASSES AND STRUCTS

class Phone {
    // variables
    let company: String
    let color: String

    // initializer, essentially the constructor of a class
    init(company: String, color: String) {
        // setting the parameters as the 
        self.company = company
        self.color = color
    }
}

// instances of the Phone class
var apple = Phone(company: "apple", color: "white")
var samsung = Phone(company: "samsung", color: "black")

/* 
class is a reference type
-> If another variable named apple2 was created and it was set equal to the variable apple, if a variable in apple changes, apple2 also changes
^ What if apple2 was changed? - no findings yet since I don't know how to change the values yet
 
struct is a value type-> if var apple2 is set equal to apple if a variable in apple changes, apple2 will not change with it as it will create a copy and so apple2 will point to a different place than apple*/
```
Overall, the videos helped expose me to similar but also slightly different concepts from Java. Through note-taking, I was able to gain a better understanding of how functions, parameters, and classes worked in Swift. In the direction of building the cookbook recipe app, the three videos I watched were helpful in that they would help me when it came to building the actual components of the app. 

I also watched another [video](https://www.youtube.com/watch?si=F1I5DG-PvTtuh2GZ&v=uSanD_pFwis&feature=youtu.be) that I saw would be helpful because it was similar if not the same app concept that my partners and I wanted to accomplish. I opened my Xcode and coded along a bit toward the beginning of the video to explore Xcode. Since I didn't dive that deep into Swift to figure out each line of code that was typed out, I only watched the first part of the video and paused watching when I realized that I wasn't absorbing much of it in my mind. 

I'm still in stage 2 of the Engineering Design Process (EDP), as I am still researching and navigating with Swift. I browsed through YouTube to find videos that would help me to build the app. Things I learned like classes and functions were crucial to building anything with Swift as they were the main and basic components of a programming language. 

Skills that I have developed in this blog entry are *how to learn* and *organization*. I explored Swift and learned it on my own with YouTube and self-tinkering. In the process of learning Swift, I noted down the times I've tinkered with Swift by watching videos and following along. In doing so, I had to keep my notes organized and neat so I could refer back to them later on. 

My freedom project goal for winter break is to finish at least half of the Swift playlist while taking notes and making my examples of the code. I want to be able to code a mini project from scratch with the concepts that I will learn from the videos to test my knowledge of Swift.

[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
