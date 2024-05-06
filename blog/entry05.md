# Entry 5
## Minimum Viable Product 5/6/24

By now, I have finished with my MVP version of the cookbook recipe app. Following the plan my partners and I had made, we collaboratively completed our tasks. While my partners worked on the homepage, I worked on the individual recipe pages. Using what I learned, I was able to set up my ideal recipe page: <br> 

<img width="343" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/d7855792-c58c-4482-8f8d-bd6a4bcd69ea"> <br>

The page had almost everything a basic recipe needed: ingredients list and instructions.


As I was making the MVP, I came across an issue. The image of the food appeared to be squished, but I wanted it to fit in the frame without the image getting squished:

BEFORE: <br>
<img width="264" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/0c18ce3b-6064-4ff7-8509-44696db396b1"><img width="233" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/577e5ad2-360e-474b-a5d7-18354dd951c5">
<br>

I tried adding `.scaledToFit()` modifier to the image, but it ended up worse: <br>
<img width="265" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/e0eb5eb4-7dae-4494-bcae-78024bccb1c3"><img width="234" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/519193e8-23c8-4a0d-b8d8-85fb2a8e2fba">
<br>

I decided to ask my partner for help with the image scaling, and she found out about the `.scaledToFill()` modifier. When I tried it, the image was successfully scaled to fit the frame:<br>

<img width="259" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/d59301b4-58cf-49e4-a594-99069639c056"><img width="231" alt="image" src="https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/d6904177-5029-4bb8-8b70-9f55d5af34b5"><br>

Alongside working on the MVP, I also continued to learn Swift. Since I wanted to use certain fonts on the app for beyond MVP, I looked into how to change text fonts.

NOTES - [FONTS](https://www.youtube.com/watch?v=4PI04Yj3Ngs)
* upload font into Swift project
* add it to a plist file
    * ![image](https://github.com/chanryc9471/apcsa-freedom-project/assets/91750491/f19e57d3-8591-4708-a0b3-1f20ae84f256)
* modifier for font
    * `.font(.custom(name: fontFamName, size: #))` (like `.font(.custon(name: ZenLoop-Regular, size: 50))`)

 
I also learned about other things, like adding page titles, scroll views, and arrays. The navigation view was helpful, as I used it for the recipe names on each page.



NOTES - [NAVIGATION TITLE](https://www.youtube.com/watch?v=nqTcAzPS3oc)
* `navigationTitle` allows you to add a title to a nav view
```java
NavigationView {
    .navigationTitle("Hello World!")
}
```


NOTES - SCROLLVIEW
```java
// ScrollView allows you to scroll on whatever is put inside
ScrollView {
    Text("Hello, How are you?")
    Text("Hello, How are you?")
    Text("Hello, How are you?")
}
```


NOTES - ARRAYS & [DICTIONARIES](https://www.youtube.com/watch?v=-uwSmesQKHE&list=PL5PR3UyfTWvfacnfUsvNcxIiKIgidNRoW&index=16)
* arrays and dictionaries are both a type of collection, both data structures
* dictionaries have keys and values
    * https://www.tutorialspoint.com/swift/swift_dictionaries.htm
 
``` java
// array of integers
var nums: [Int] = [1, 2, 3,]

// array of strings
var names: [String] = [Chanry, Bob, Billy]

// array with more than one datatype
var anything: [Any] = [Chanry, 1.23, 5]

// iterating through array (integers)
for num in nums {
    print(num)
}

// dictionary of strings as keys and integers as values
var characters: [String: Int] = ["chanry": 1, "bob": 2, "billy": 3]

// iterating through a dictionary
for (key, value) in characters {
    print(key)
    print(value)
}

// print will be like:
// chanry
// 1
// bob
// 2
// billy
// 3
``` 

I am currently on stages 5 and 6 of the EDP, which involve creating a prototype and testing and evaluating it respectfully. My partners and I have been creating the MVP, and in doing so, we tested and evaluated the app as needed. We will soon advance and add more features beyond the MVP.

Skills I have achieved in this blog entry are *communication* and *time management*. While coding on Xcode on our project, sometimes unsaved changes would "disappear" after pulling from the GitHub repository, which made it difficult for us to code and update each other on the progress. This led to us communicating way more, as we needed to ensure the code didn't disappear. I also worked on my time management skills, as it was crucial that I follow the MVP plan to ensure that I meet the deadline for MVP. I held myself accountable for the components that had to be done before a certain time and allocated time to work on my MVP.


[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
