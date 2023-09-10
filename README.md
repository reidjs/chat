# The Mob Programming Language
`Mob` is a programming language with syntax optimized for mobile device keyboards.

## Why?
JavaScript, C, and most other conventional programming languages are cumbersome to write from a mobile keyboard, while `Mob` is optimized to be written on your phone without any special software. For example, 
1. Phone keyboards tend to start each new line with the shift (capital) key on.
  - In `Mob`, a capital letter (A-Z) denotes the beginning of a statement. 
2. Special characters that most languages rely on like `(&|{};)` are difficult to write from a mobile device.
  - `Mob` prefers short words like `and`, `or`, and `fun` instead of `&&`, `||` or `function`. 

# Code Examples
`>>` indicates the output from the program

## Hello, world
```
Print "Hello, world"
>> Hello, world
```


## Comments
```
Comment this line will be ignored because it starts with the word "comment"
```

```
Comments 
These lines will be ignored until the word capitalized word "end" 
because of the 's' at the end of the word "comments."
End
```

## Math
Note: variables are case insensitive, Product is the same as product

```
Sum is 5 plus 5
Product is sum times 10
Print product
>> 100
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
Note: "increment i" is eqivalent to i += 1 in most languages

```
I is 0
While i less than 10
Print i
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


## Contact
If you find Mob interesting, potentially useful, or a bit silly, contact me! You can find my email in my GitHub profile, just mention `Mob lang` or The Mob Programming Language, or something like that in the subject and I will respond as soon as possible. 

Thank you,

Reid JS
