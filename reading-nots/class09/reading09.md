# Enumerations in Python

Enumerations in Python are implemented using the `enum` module. Enums are created using classes and provide a way to create more readable and self-documenting code by using meaningful names instead of arbitrary values.

## What are Enums and Why are They Useful?
Enums are a set of symbolic names bound to unique values. They help in creating readable and self-documenting code, centralizing name values for easier maintenance, and providing type safety to reduce errors.

## Properties of Enum
- Enums can be displayed as strings or `repr`.
- Enums can be checked for their types using `type()`.
- The `name` keyword is used to display the name of the enum member.

## Advantages of Using Enums
- **Ease of Maintenance**: Centralizes the definition of name values.
- **Readability and Self-Documentation**: Provides meaningful names to values.
- **Type Safety**: Ensures only valid values are used.
- **Reduced Risk of Errors**: Helps prevent the use of incorrect values.

## Accessing Enum Members
Enum members can be accessed by value or name. They can also be iterated over and used in dictionaries or sets due to their support for hashing.

## Comparing Enums
Enumerations support identity and equality comparisons, allowing for checks between enum members.