# The M Programming Language
The first programming language optimized for developing software from a mobile device. 

## What problem is this trying to solve?
JavaScript, C, and most other conventional programming languages are cumbersome to write from a mobile keyboard. `M`'s syntax is optimized to be written by a mobile phone keyboard. For example, 
1. Since phones tend to start each new line with a capital, a capital letter (A-Z) denotes the beginning of a statement. 
2. `M` Avoids special characters that most languages rely on (&|{};), and prefers A-Z where possible. 

## Hello, world
```
Print "Hello, world"
>> Hello, world
```
*>>* represents the output from running the program

## Math
```
Sum is 5 plus 5
Var product is sum times 10
Print product
>> 100
```

## Comments
```
Comment this line will be ignored because it starts with the word "comment"
```

```
Comments these lines will be ignored until the word end (with a capital e) because
of the s at the end of the word "comments"
End
```

## Logic
```
X is 5
If x equals 5
Print "yay!!!!"
End
>> yay!!!!
```

```
X is true
Y is true
Z is false
Comment note that variables are case insensitive, X is the same as x
If x and y or z
Print "yay!!!!"
End
>> yay!!!!
```

## Loops
### For loop
```
For i is 0, i less than 10, increase i
Print i
End
>> 0123456789
```
### While loop
```
I is 0
While i less than 10
Print i
Comment "increment i" is eqivalent to i += 1 in most languages
Increment i
End
>> 0123456789
```

## Functions
```
Fun add a, b
Return a + b
End
Call add 5, 5
>> 10
```

## Open Questions
How can we enable the user to run and debug their code from the phone?
  - A solution might be a website like [replit](https://replit.com/) that you can easily paste code snippets into and see the output. 


## Request for Help
If you find m lang interesting, potentially useful, or a bit silly, contact me! You can find my email in my GitHub profile, just mention `m lang` or The M Programming Language, or something like that in the subject and I will respond as soon as possible. 

Thank you,

Reid JS
