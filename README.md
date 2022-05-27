# descriptive

A programming language where things are named with the descriptive comments following an item.

A simple example:
```
; this is a comment

use System
use System Collections Generic

namespace Descriptive Test

class   ; test class
  fn    ; "Main" method
    Console WriteLine "Welcome to descriptive"    ; no parentheses required unless you need to specify which parameters belong to which call
    Console WriteLine
    Console WriteLine "Please enter your name"
    Console ReadLine        ; user name
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
    the user older    ; the user Age
    Console WriteLine "Your age has been updated to {the user Age}"
    
    ; generics and accessors
    new List of string            ; my list
    my list Add "first value"
    my list Add "second"
    Console WriteLine my list 0   ; print out the first value
    "new first value"             ; my list 0

class     ; person
  string  ; Name
  int     ; Age
  
  new name string, age int
    name  ; Name
    age   ; Age
  
  fn    ; print details
    Console Writeline "{Name} is {Age} years old."
  
  fn    ; get "older" age, the method is just called older since it's in quotes
    return this Age + 1
```
