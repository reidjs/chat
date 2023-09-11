# A guide to Lex & Yacc
https://arcb.csc.ncsu.edu/~mueller/codeopt/codeopt00/y_man.pdf


# Practical parsing with Flex and Bison
https://begriffs.com/posts/2021-11-28-practical-parsing.html
Lex should come preinstalled on mac
0. Create rules file
`catcot.l`
```
%{
#include <stdio.h>
%}

%%

cot { printf("portable bed"); }
cat { printf("thankless pet"); }
cats { printf("anti-herd"); }
```
1. Turn input file into an intermediate C file
`lex -t catcot.l > catcot.c`
2. Compile the .c file
`cc -o catcot catcot.c -ll`
3. Example
`echo "the cat on the cot joined the cats" | ./catcot`
>>the thankless pet on the portable bed joined the anti-herd