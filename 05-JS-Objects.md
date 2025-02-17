```js
Day 5: Objects (M)

1. OBJECT CREATION

  • Literal Notation
    Using { key: value } allows you to create objects quickly.
    Example:
    let person = { name: "Alice", age: 30 }

  • Constructor Functions
    Constructor functions enable creating objects using the new keyword.
    They serve as blueprints for similar objects.
    Example:
    function Person(name, age) {
      this.name = name
      this.age = age
    }
    let person1 = new Person("Bob", 25)
    (Detailed usage and inheritance with constructor functions are covered in advanced topics)

2. ACCESSING & MODIFYING PROPERTIES

  • Dot vs. Bracket Notation
    Dot notation is used when property names are valid identifiers.
      person.name returns "Alice"
    Bracket notation is ideal for dynamic keys or property names that are not valid identifiers.
      person["age"] returns 30

  • Adding, Updating, and Deleting Properties
    Properties can be added or updated using simple assignment.
      person.email = "alice@example.com"
    To remove a property, use the delete operator.
      delete person.age

3. OBJECT METHODS & UTILITIES

  • Defining Methods
    Functions can be assigned as properties to create methods within an object.
      let person = {
        name: "Alice",
        greet: function() {
          return "Hello, " + this.name
        }
      }
    The this keyword inside a method refers to the current object context.

  • Utility Functions
    Object.keys() returns an array of an object's own property names.
      Object.keys(person) yields ["name", "greet", "email"]
    Object.values() returns an array of an object's own property values.
      Object.values(person) yields ["Alice", function() { ... }, "alice@example.com"]
    Object.entries() returns an array of key-value pair arrays.
      Object.entries(person) yields [["name", "Alice"], ["greet", function() { ... }], ["email", "alice@example.com"]]

  • JSON Basics
    JSON.stringify() converts an object into a JSON-formatted string.
      JSON.stringify(person) produces a string representation of the object.
    JSON.parse() converts a JSON string back into an object.
      JSON.parse('{"name":"Alice","age":30}') returns an object.

  • A Glimpse into Prototypes
    Every object in JavaScript has a prototype from which it can inherit properties and methods.
    This prototype chain is the foundation for inheritance in JavaScript.
    (In-depth exploration of prototypes and inheritance is covered in advanced topics)

IMPORTANT TIPS & NOTES:
  • Objects are fundamental for organizing related data and functionality.
  • Use literal notation for creating simple objects and constructor functions when building multiple similar objects.
  • Prefer dot notation for straightforward property access and bracket notation for dynamic or unconventional property names.
  • Utilize utility methods like Object.keys(), Object.values(), and Object.entries() to inspect and debug objects.
  • A solid understanding of the prototype chain enhances your grasp of JavaScript’s object-oriented capabilities.

END OF NOTES

```
