# Code Refactoring: Learn Code Smells And Level Up Your Game! [YouTube](https://www.youtube.com/watch?v=D4auWwMsEnY)
## Code Smells
for a List of code smells you can go [here](https://refactoring.guru/smells)
Code refactoring is hard, and people say they know about code smells but they don't;
Here are 22 most precise code smells.

- Alternative Classes / Different Interfaces
- Inappropriate Intimacy
- Parallel Inheritance
- Comments
- Data Class
- Data Clumps
- Divergent Change
- Duplicated Code
- Feature Envy
- Incomplete Library Client
- Large Class
- Lazy Class
- Long Method
- Long Parameter List
- Message Chains
- Middle Man
- Primitive Obsession
- Refused Bequest
- Shotgun Surgery
- Speculative Generality
- Switch Statements
- Temporary Field

People prefix code smells with BAD keyword. 
They say Bad Smells, but really but really the definition of a code smell is that it might indicate a problem not
that it does it might and so you don't you don't have an obligation to filter out all the smells it's actually important
that you not and it's worth getting its it's also worth getting for me with code smells because they have such great names.

above CodeSmells are categorized into 5 Parts
#### Bloaters
They make code bigger than it needs to be where we use them
- Long Method
- Large Class
- Long Parameter List
- Primitive Obsession *(Use of primitives instead of small objects for simple tasks (such as currency, ranges, special strings for phone numbers, etc.)*

#### Tool Abuser
- Switch Statements 
- Refused Bequest
- Alternative Classes / Different Interfaces
- Temporary Field

#### Change Preventer
- Divergent Change
- Shotgun Surgery
- Parallel Inheritance
- Hierarchies

#### Dispensable
- Lazy Class
- Speculative Generality
- Data Class
- Duplicated Code

#### Couplers
- Feature Envy
- Inappropriate Intimacy
- Massage Chains
- Middle Man

## Refactoring
Like code smells, Refactoring have types or you can say recipes.
All of the refactoring work in the same. it have very specific definition,
[Here](https://refactoring.guru/refactoring/techniques) for detailed content

> To rearrange code without changing its behavior

So every code smell have name and every refactoring type has name and they have recipe.
> Every code smell maps to Curative Refactoring Recipe


