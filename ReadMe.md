# 100 Days with SwiftUI
### by [Hacking with Swift](https://www.hackingwithswift.com/100/swiftui/3)

## Notes

### Day 1 __Simple Types__ - 9/23/2019
- Variables
- Strings and Integers
- Multi-line strings
- Doubles and booleans
- String interpolation
- Constants
- Type annotations

### Day 2 __Complex Types__ - 9/24/2019 
- __Arrays__
- __Sets__
- __Tuples__
    - created by placing items inside parenthesis
    - You can name tuple items
    - You can access tuple items using numerical positions
    - Tuples store values together in a single value
    - You can’t change the types of tuple items
    - Tuples are fixed in size
- __Arrays vs sets vs tuples__
- __Dictionaries__
- __Dictionary and default value__
    - ```let venus[2, default: “Planet X”] //gives a default value if key 2 does not exist```
- __Creating empty collections__
    - ```var favoriteColors = Dictionary<String, String>() //is valid, and if creating empty dic then use comma```
    - ```var friends = Set<String>() //is how you create an empty set of string```
- __Enumerations__
    - Directions (North,S,E,W) and Error types are best choice for enums as there is only a fixed number of errors/directions you can issue 
- __Enum associated values__
    - ```enum Building { case skyscaper(floors: Int) } //this creates a case called skyscraper with the asssociated value floors```
- __Enum raw values__
    - Raw values let us give each of our enum cases a value so they are more than just names
    - Which of these statements about enums with raw values are true?
        - This is optional, but you can give each case specific values if you want, and it gives us fine-grained control when needed
        - Integer raw values count from 0 automatically ```//which is modifiable to whatever u want```
        - You don’t need to use raw values
        - Raw values and associated values are not the same. Associated values attach extra data to an enum case; raw values are underlying data types for each case
        - You can use strings and integers (most common) for raw values
        - Raw values let us create enum values dynamically. We can create an enum from its raw value
        - Raw values let us give meaning to enum cases. They let us say that earth has an underlying value of 3, for example
        - Raw values are optional
- __Complex types: Summary__

### Day 3 __Operators and Conditions__ - 9/25/2019
- __Arithmetic Operators__
    - ```var result = 11 % 6 //11 divides into 6 once, leaving remainder 5.```

- __Operator overloading__
    - ```var result = true * 2 //is not valid```
    - ```var resultArr = ["Red", "Green"] + ["Blue"] //is valid ```
- __Compound assignment operators__
- __Comparison operators__
- __Conditions__
    - you cannot compare a Double to an Integer
- __Combining conditions__
- __The ternary operator__
- __Switch statements__
    - Switch statements require some sort of value to check at the beginning.
    - You can use fallthrough as many times as you want.
    - Switch statements must be exhaustive in Swift, which means that all possible cases are catered for.
    - Code from the following case will be run if you use fallthrough.
        - By default Swift will stop executing code in a switch block once it reaches the end of a case that was matched.
- __Range Operators__
    - ... and ..<
- __Operators and conditions summary__
    - let passingGrade = 70...100 //is a valid code in Swift
    
### Day 4 __Looping__ - 9/26/2019
- __For loops__
    - ```var speeds = (65, 58, 72)
        for speed in speeds {
            print("You were driving at \(speed)km/h.")
        } //You cannot loop over a tuple like this.```
- __While loops__
- __Repeat loops__
    - like do-while loop from C++
- __Exiting loops__
    - break
- __Exiting multiple loops__
    - You can exit more than one loop at a time
    - We use names rather than numbers for breaking out of a specific loops.
    - You can embed one loop inside another
- __Skipping items__
    - Calling break skips the remainder of the current loop, but calling continue skips only the current item.
- __Infinite loops__
- __Looping: Summary__
    - ```outer: for i in 1...10 { //example of naming and breaking from outer loop
        for j in 1...10 {
            let product = i * j
            print("Product is \(product)")
            break outer
        }```
    }


### References:
Emphasis, aka italics, with *asterisks* or _underscores_.
Strong emphasis, aka bold, with **asterisks** or __underscores__.
Combined emphasis with **asterisks and _underscores_**.
Strikethrough uses two tildes. ~~Scratch this.~~
