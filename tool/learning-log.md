# Tool Learning Log 

Tool: **Flutter**

Project: **Cookbook App**

---

10/27/23: [Intro & Setup](https://youtu.be/1ukSR1GRtMU?si=T5thSLF81Ldu1RCD)
* Git: https://git-scm.com/downloads
* Flutter: https://docs.flutter.dev/get-started/install
* VS Code: https://code.visualstudio.com/download

* I originally wanted to do Swift, but I saw Flutter and how it was cross-platform so I liked that better
   * https://www.youtube.com/watch?v=HJDCXdhQaP0&t=8s
     * I liked Xcode better
     * functions looked more cleaner and easier to use 

---

10/29/23: [Dart Primer](https://youtu.be/FLQ-Vhw1NYQ?si=tkzexejwfiK54_x8)
* Dart Playground: https://dartpad.dev/
   * went on it to test out all the variables, similar to what I learned in Java thus far
__Basics__
* instead of `boolean` (Java), it's `bool`
* variables are similar to Java
* `dynamic` can be used
* use `let` if the value won't be changed
**PAUSED AT 15:47 IN VIDEO**

---

10/30/23: 
* continued with the [Dart Primer](https://youtu.be/FLQ-Vhw1NYQ?si=tkzexejwfiK54_x8) video
<img width="960" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/08270aae-4433-4bd0-ad0f-44c2dd867131">
<br>
^ tried following along with the video to get a hang of the dart playground (syntax is similar to Java)

* When I followed along with the video, it showed that I didn't need to initialize the variables yet, but then I saw the error comments telling me to initialize, which finally got my code to work (old video so it probably used to be that one didn't have to initialize for the variable to work
* learned about inheritance and extending classes

**Overall it seems that Flutter is similar to Java and it seems relatively suitable for the app I want to make. However, I want to make an IOS app Xcode is needed for me to make an IOS app on Flutter.**

---

11/5/23:
* followed along this [video](https://youtu.be/C5lpPjoivaw?si=fC4CxmCT-LlnvXe7) and made this:
<img width="960" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/cd33cf65-92dd-4de5-9a86-39567dd87324">
<br>

* first step to forming an app UI
  * it was hard to make the button even though I followed how netninja did it (might try it again next time I tinker)
* next steps: try to see what Swift has to offer to make my final decision about what tool I am using.

---

Tool: **Swift**

11/12/23:
[Swift Youtube Playlist](https://www.youtube.com/playlist?list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW)
* watched parts 1 and 2 on variables and constants
  * syntax is similar to how javascript declares and initializes variables

* found out about Swift playground and possibly use it to make the app without the need for Xcode
  
![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/bcad02ef-f3e2-4491-a989-6a8edf644dd3)

---

11/19/23:
* watched [part 3 - types](https://youtu.be/48v8FH46mQs?si=-dn7eozv6znIF_Dg)
   * learned about types
     * Swift assumes variable type but it can be declared like `var varName: dataType = "anything here"`
   * do `import UIKit` to import user interface elements

* watched [part 4 - functions & parameters](https://youtu.be/fffG55Ei1Qc?si=k-NBPZAnnPZkBKlC)
```swift
func funcName(paramName1: value, randomNum: Int) -> expectedReturnVal {
return paramName1 + randomNum
}
```
 * learned how to make/call a function, parameters, how to make a function return something, and how a return type is set  in a function

---

11/26/23:
* watched a [video](https://youtu.be/uSanD_pFwis?si=F1I5DG-PvTtuh2GZ) to get a sense of SwiftUI
    * followed along with the video on my own Xcode and did what the YouTuber did and got a feel of how it was like coding with SwiftUI
    * Didn't fully understand what I was typing in but I started to understand some little bits of what was what
    * stopped at 4:43 in the video

---

12/3/23:
* continued with the [video](https://youtu.be/uSanD_pFwis?si=F1I5DG-PvTtuh2GZ)
  *  learned about SF Symbols - https://developer.apple.com/sf-symbols/
    * tried to get SF Symbols to work but it didn't so I'll try again next time
    * did not try to code along with the video because it looked too complicated at the moment so I just watched how the person did it
    * stopped video at 13:42
 
12/10/23: 
* decided to ditch the previous video because it wasn't helpful and I got too confused with everything since there was no explanation as to the things she coded
* watched [part 5 - classes and structs](https://youtu.be/ys3dPSKssgk?si=P-dvOx54FKktY_2P) of the playlist from before
  
* from the video I made my version of a class and its variables and indicator:
![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/17af863d-a759-4db2-bb0b-eaf53636e9c9)<br>

* what I learned from the video on the differences between classes and structs
![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/bc772dc0-0788-4965-9f83-32b67fb983b8)<br>

1/1/24:
* watched part 6 [video](https://www.youtube.com/watch?v=8Z0mImrIITA&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=6)<br>
![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/82ef86a0-c808-4918-86a4-954a4ae6134c)<br>

* this video was easy since it was fairly similar to how Java is, except the `for in` which was new
  * the `for in` does the same as the `for each`
* watched part 7 [video](https://www.youtube.com/watch?v=9K89xEuSiYA&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=7)
  * paused the video at 7:39 because I got error messages while I was coding along
    * kept saying something about "Expressions/Statements are not allowed at the top level"
    * went online to search for answers about the error message (stack overflow) but I couldn't understand it (will research more
    * while clicking around to get the error message to go away, I found a [documentation](
https://docs.swift.org/swift-book/documentation/the-swift-programming-language/) for Swift
      * will browse the documentation more next time
 
1/7/24:
* finished part 7 video
  * optionality is a good way to represent errors
    * gives flexibility with assigning values of a particular variable
   
* followed along [part 8 video](https://www.youtube.com/watch?v=rBotA3jwWkY&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=8)
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
* operators are the same as Java
*  will watch part 9 and part 10 (see what I learn from that and maybe code a mini project)

1/15/24:
* watched [part 9](https://www.youtube.com/watch?v=DTd7HHSAw-4&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=9)
```java
// guard statements
// - they are much more "cleaner" (simpler) than if/else statements
guard conditional1, conditional2 else { wtvHappensIfConditionalsAreFalse }
  // code that will run if conditions are met
```
* using guards to unwrap optionals and also a simpler way than if/else statement are the most common
<img width="331" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/24a95701-f991-4783-89de-a54bc5b87e78">
^^ optional


1/21/24:
* watched [part 10](https://www.youtube.com/watch?v=_qxm-MvRw_Y&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=10)
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
* enum is a special data type that allows variables to be predefined
* stopped video at 8:31


1/29/24:
* continued with part 10
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
* since `current` is set to `states.InProgress` (from code snippet in last tinker log), whatever code that is for `.InProgress will run



3/3/24:
* watched part 11 of the swift playlist
  * learned about protocols
    * basically like a place to declare your variables and functions before initializing it
    * used for when say those variables and functions can be used in other classes besides just one
```java
// protocols
protocol AnyFun {
  var anything: String { get set } // the get set is so the classes can get and set the value of the var

  func anyWords()
  func haveApple() -> Bool

// class
class haveApple() ->  {
  var anything: String
  init(var anything: String) {
    self.color = color
  }

}
}    
<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

