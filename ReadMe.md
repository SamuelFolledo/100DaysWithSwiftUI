# 100 Days with SwiftUI
### by [Hacking with Swift](https://www.hackingwithswift.com/100/swiftui/3)

## Notes

- Day 1 - 9/23 Simple Types
    - Variables
    - Strings and Integers
    - Multi-line strings
    - Doubles and booleans
    - String interpolation
    - Constants
    - Type annotations

- Day 2 - 9/24 Complex Types
    - Arrays
    - Sets
    - Tuples
        - created by placing items inside parenthesis
        - You can name tuple items
        - You can access tuple items using numerical positions
        - Tuples store values together in a single value
        - You can’t change the types of tuple items
        - Tuples are fixed in size
    - Arrays vs sets vs tuples
    - Dictionaries
    - Dictionary and default value
        - ```let venus[2, default: “Planet X”] //gives a default value if key 2 does not exist```
    - Creating empty collections
        - ```var favoriteColors = Dictionary<String, String>() //is valid, and if creating empty dic then use comma```
        - ```var friends = Set<String>() //is how you create an empty set of string```
    - Enumerations
        - Directions (North,S,E,W) and Error types are best choice for enums as there is only a fixed number of errors/directions you can issue 
    - Enum associated values
        - enum Building { case skyscaper(floors: Int) } //this creates a case called skyscraper with the asssociated value floors
    - Enum raw values
        - Raw values let us give each of our enum cases a value so they are more than just names
        - Which of these statements about enums with raw values are true?
            - This is optional, but you can give each case specific values if you want, and it gives us fine-grained control when needed
            - Integer raw values count from 0 automatically //which is modifiable to whatever u want
            - You don’t need to use raw values
            - Raw values and associated values are not the same. Associated values attach extra data to an enum case; raw values are underlying data types for each case
            - You can use strings and integers (most common) for raw values
            - Raw values let us create enum values dynamically. We can create an enum from its raw value
            - Raw values let us give meaning to enum cases. They let us say that earth has an underlying value of 3, for example
            - Raw values are optional
    - Complex types: Summary 







References:
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
Emphasis, aka italics, with asterisks or underscores.

Strong emphasis, aka bold, with asterisks or underscores.

Combined emphasis with asterisks and underscores.

Strikethrough uses two tildes. Scratch this.
