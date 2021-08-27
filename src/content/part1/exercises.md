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
create a program which prints these lyrics using three (3) `Console.WriteLine`s.

</Exercise>

<Exercise title={'003 Bonnie Tyler with line changes'}>

Let's refine our program. Print the same message:  
```
Once upon a time
I was falling in love
Now I'm only falling apart
```
This time, use only one `Console.WriteLine`.

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

Change it, so that it prints `Passport and a toothbrush!`
Do not change the line containing `Console.WriteLine`, only change the content of the variable!

</Exercise>

<Exercise title={'003 Bonnie Tyler with line changes'}>

You will find following structure in the exercise:
  
```cpp
using System;

namespace Exercise005
{
    class Program
    {
        public static void Main(string[] args)
        {
            string name = "Ada Lovelace";
            // Write your code here:           
        }
    }
}
```

Modify the code, so that it prints `Hello Ada LoveLace!`
Do not modify the variable content!

</Exercise>

<Exercise title={'006 Print input'}>

Create a program, that asks user for a string. After the user has given the string (written text and pressed enter), the program will print the given line. Example output with `Hello` as input (input marked with `>` for clarification):

```console
Give input!
> Hello
Hello
```

</Exercise>

<Exercise title={'007 Triple hello'}>

Create a program, that asks user for a string. After the user has given the string (written text and pressed enter), the program will print the given line 3 times. Example output with `Hello` as input:

```console
Give input!
> Hello
Hello
Hello
Hello
```

</Exercise>

<Exercise title={'008 Greeting'}>

Create a program, that asks user for their name and greets them. Example output with `Ada` as input:

```console
What is your name?
> Ada
Hello Ada!
```
Notice the exclamation mark.

</Exercise>

<Exercise title={'009 Conversation'}>

Create a program, that simulates a small conversation. The program will tell three lines, and expects two user inputs. Example output:

```console
Hello, how are you?
> Fine, thanks.
That's interesting, tell me more
> I learn coding
Thank you for sharing!
```

</Exercise>

<Exercise title={'010 Name and Profession'}>

Create a program, that asks the user for a name and a profession. Then make the program to write a little story with this information. Here is an example story with inputs `Ada` and `Data Scientist`.

NOTICE! Every `Ada` and `Data Scientist` in the story are the inputs by the user. Remember to save the `Console.ReadLines` into variables and use them as parts of the story!

```console
I will tell a story, but I need some information.
Give a name for main character:
> Ada
Give the character a profession:
> Data Scientist
Here is the story:
Once upon a time there was a Data Scientist called Ada
On her way to work, Ada often pondered what being Data Scientist meant to them.
When you work as a Data Scientist you meet interesting people.
Ada enjoys their work as Data Scientist, The end.
```

</Exercise>

<Exercise title={'011 Print variables'}>

Create a program, that asks the user for a name and a profession. Then make the program to write a little story with this information. Here is an example story with inputs `Ada` and `Data Scientist`.

NOTICE! Every `Ada` and `Data Scientist` in the story are the inputs by the user. Remember to save the `Console.ReadLines` into variables and use them as parts of the story!

```console
I will tell a story, but I need some information.
Give a name for main character:
> Ada
Give the character a profession:
> Data Scientist
Here is the story:
Once upon a time there was a Data Scientist called Ada
On her way to work, Ada often pondered what being Data Scientist meant to them.
When you work as a Data Scientist you meet interesting people.
Ada enjoys their work as Data Scientist, The end.
```

</Exercise>