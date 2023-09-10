# I. The Mob Scanner 
The scanner reads in the source code and groups it into `tokens` - the meaningful "words" and "punctuation" that make up Mob's grammar. Think of it like a big switch statement.
1. Error handling: if a mistake is made in the source code, report the line number to the user.
2. Lexemes and Tokens: group the characters from the source code into `lexemes`. Then, bundle those with other data (e.g, take into account reserved words) to produce `tokens`
3. Regular Languages and Expressions
4. Operators 
5. String literals
6. Number literals
7. Reserved words and identifiers