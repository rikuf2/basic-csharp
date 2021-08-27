---
title: 'Exercises'
nav_order: 6
hidden: false
---

<Exercise title={'001 Hello World'}>
The basic structure of a program is given in the exercise:

```cpp
using System;

namespace Exercise001
{
    class Program
    {
        public static void Main(string[] args)
        {
            // Add your code here:
            
        }
    }
}
```

The line `\\Add your code here:` is a comment. The composer does not compose it, so you do not have to worry about it. You can remove it, if you want.

Create a program that writes the text `Hello World!` into the console. The program contains the basic structure pictured above.

</Exercise>


<Exercise title={'002 Bonnie Tyler'}>

Let's write some more. Bonnie Tyler once sang about feelings, that also apply to coding:  
```
Once upon a time
I was falling in love
Now I'm only falling apart
```
create a program using 3 Console.WriteLines, that prints these lyrics.

</Exercise>

<Exercise title={'003 Bonnie Tyler with line changes'}>

Let's refine our program. Print the same message:  
```
Once upon a time
I was falling in love
Now I'm only falling apart
```
This time, use only one Console.WriteLine.

</Exercise>

<Exercise title={'004 First variable'}>

The exercise has following structure:

```cpp
using System;
 
namespace Exercise004
{
    public class Program
    {
        public static void Main(string[] args)
        {
            string message = "Passport and floss!";
            Console.WriteLine(message);
        }
    }
}
```

Change it, so that it prints **Passport and a toothbrush!**
Do not change the line containing Console.WriteLine, only change the content of the variable!

</Exercise>