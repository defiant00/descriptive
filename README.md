# descriptive

A programming language where things are named with the descriptive comments following an item.

A simple example:
```
; this is a comment

use System

namespace Descriptive Test

class   ; my test class
  fn()  ; my "Main" function
    Console WriteLine "Welcome to descriptive"    ; no parentheses needed unless you need to specify nesting
    Console WriteLine
    Console WriteLine "Please enter your name"
    Console ReadLine    ; user name
    Console Writeline "Hello {user name}"
    Console WriteLine "How old are you?"
    Console ReadLine        ; age
    Convert ToInt32 age     ; converted age
    if converted age > 100
      Console WriteLine "That's impressive!"
    Console WriteLine "Counting to {converted age}..."
    loop converted age      ; iterator
      Console WriteLine iterator
    Console WriteLine "Here are the letters of your name:"
    loop user name  ; we can reuse "iterator" if we want
      Console WriteLine iterator
    new person user name, converted age   ; the user
    the user print details
    Console WriteLine "The user name from the object: {the user Name}"
    Console Writeline "If you were older, you might be {the user older}"

class   ; person
  string Name
  int Age
  
  new string name, int age
    Name = name
    Age = age
  
  fn    ; print details
    Console Writeline "{Name} is {Age} years old."
  
  fn    ; get "older" age, the method is just called older since it's in quotes
    return this Age + 1
```
